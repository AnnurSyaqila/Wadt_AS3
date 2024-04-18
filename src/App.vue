<template>
  <div class="container mx-auto p-4">
    <div class="flex flex-col items-center">
      <img
        src="./assets/Annur-compressed.jpeg"
        class="profile-image mb-4"
        alt="Profile Picture"
      />
      <h1 class="text-2xl font-bold text-blue-600">
        An'nur Syaqila Syuha'daa binti Roslin
      </h1>
      <!-- short description -->
      <p class="text-gray-800 mb-4">22FTT1503| Web Developer | DWDT08</p>
      <!-- Add your hobbies, interests, etc. here -->
      <p class="text-gray-700 mb-4">
        Im still in the age of wanting to explore and learn new things. I gained
        an interest in nature hiking and looking forward to explore more places
        outside of my comfort zone. before this, I was a taekwondo athlete but I
        decided to retire and become a referee instead. I'm really comfortable
        with being alone yet I would still enjoy company of others. Other than
        that, I really love cats and Batman is my bestfriend. He's so playful
        and can be very annoying sometimes especially when he try to wake me up
        in the morning. I'm also a web developer and I'm still learning to
        improve my skills. I enjoy learning but I personally won't take it as my
        profession one day. perhaps Im looking forward to become a project
        manager someday.
      </p>
    </div>
  </div>
</template>

<style scoped>
/* Style for profile image */
.profile-image {
  width: 200px; /* Set desired width */
  height: 200px; /* Set desired height */
  object-fit: cover; /* Prevent image from stretching and maintain aspect ratio */
  border-radius: 50%; /* Make the image round */
}

/* Random design styles */
.container {
  background-color: #f7fafc;
  padding: 2rem;
  border-radius: 0.5rem;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
h1 {
  font-family: "Arial", sans-serif;
}
p {
  line-height: 1.5;
}
</style>
