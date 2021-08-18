A Small Addition
Here's one thing I forgot to do in the last lecture: Make the button caption dynamic.

In the FriendContact.vue file, change the <button> from

<button @click="toogleDetails">Show Details</button>

to

<button @click="toogleDetails">{‌{ detailsAreVisible ? 'Hide' : 'Show' }} Details</button>

Also add the following font import to the <style> section in the App.vue file (right at the beginning of the style section).

@import url('https://fonts.googleapis.com/css2?family=Jost&display=swap');