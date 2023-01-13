<template>
  <div class="info">
    <div class="title">
      <img src="https://jonathanchoi.cdn.imgeng.in/assets/me.jpg" />
      <h3>Developer Support Engineer</h3>
      <h3>ScientiaMobile</h3>
      <h4>GWU Coding Certificate Awarded: March 13th, 2020</h4>
    </div>

    <div class="about">
      <h3>A little about me</h3>
      <p>
        Born and raised in Virginia, I am a graduate of George Mason University
        with a Bachelor's of Science in Public Health. I have worked in a
        variety of fields, from butcher's assistant to specimen management
        technician, and I am now pursuing a career in web development. I have
        always had a passion for building models as a child and as an adult, web
        development has been a perfect fit for my tendencies of fiddling and
        fitting various pieces together. After hearing about the GWU Bootcamp
        from a coworker, I decided to take the leap of faith. I am really
        enjoying the program and really proud the progress that I have been
        making having had no prior experience with web development.
      </p>
      <p>
        The correlations between web development and my hobbies has been eye
        opening. I have always had an interest in computers, but my interest had
        been surface level in terms of hardware,web-surfing, and computer games.
        My father has always been technologically savvy and wished to impart
        onto me the knowledge of building a computer. I built my current desktop
        as a freshman in college and have been upgrading it incrementally
        throughout the years. As a child I have always enjoyed fiddling with
        Legos, plastic model kits, and sculpting. Web design take these
        interests of mine and gives me the freedom to create from start to
        finish in a way that I find very engaging and satisfying. As a fledgling
        web developer, I hope to gain all the experience and absorb all the
        information within the GWU Bootcamp and becoming both competent and
        proactive in learning and developing.
      </p>
      <p>
        I have recently completed the GWU Coding BootCamp on March 13th, 2020. I
        am currently seeking a new opportunity in Web Development and would be
        honored if you looked through my portfolio. Though I may be lacking in
        experience, I will make up the difference by putting in as much effort
        as humanly possible. Passion is what I feel when it comes to web-design
        which has been wavering within my past endeavors. I would very much
        appreciate any and all feedback. Thank you for visiting my web page and
        please feel free to send me a message below.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainCard",
  props: {
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  width: 10rem;
  border-radius: 50%;
}
.title {
  text-align: center;
  border-radius: 25px;
  padding: 1rem;
  grid-area: title;
}
.about {
  /* margin-left: 2rem; */
  padding: 1rem;
  grid-area: about;
}
.info {
  background-color: white;
  max-width: 80%;
  margin: auto;
  border-radius: 25px;
  display: grid;
  grid-template-areas: "title about";
  grid-template-columns: 1fr 3fr;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px;
}

</style>
