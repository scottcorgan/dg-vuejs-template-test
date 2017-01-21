<template>
  <div class="container">
    <section class="hero">
      <header>
        <h2>Careers</h2>
        <share />
      </header>
      <div class="hero-intro">
        <h3>
          We exist to share the truth that God is most glorified in us
          when we are most satisfied in him.
        </h3>
        <p>
          Desiring God is a web ministry with more than 10,000 resources to
          help people find truth, purpose, and satisfaction that will never
          end. <a href="">Watch this video to learn more</a>.
        </p>

        <dg-button>Inquire</dg-button>
      </div>
    </section>
    <section class="reach">
      <header>
        <h3>Our Products and Reach</h3>
        <p>
          Through desiringGod.org and our three mobile apps, God is
          enabling us to reach new people all across the globe with our
          content.
        </p>
      </header>
      <ul class="">
        <li>Hey</li>
        <li>Hey</li>
        <li>Hey</li>
        <li>Hey</li>
        <li>Hey</li>
      </ul>
    </section>
    <opportunities />
  </div>
</template>

<script>
import share from './share'
import opportunities from './opportunities'
import button from './button'

export default {
  components: {
    share,
    opportunities,
    'dg-button': button
  }
}
</script>

<style scoped>
.hero {
  margin-top: -30px;
  padding: 30px 50px 40px 50px;
  background-image: url(http://image.desiringgod.org/careers-o6vh66tn-en/careers-o6vh66tn.jpg?0);
  background-size: cover;
  text-align: center;
}

.hero header {
  text-align: left;
  display: flex;
  border-bottom: 1px solid #eee;
  line-height: 55px;
  align-items: center;
}

.hero header h2 {
  font-size: 45px;
  flex: 1;
}

.hero-intro {
  padding: 50px 0;
  max-width: 960px;
  margin: 0 auto;
}

.hero-intro h3 {
  font-size: 36px;
  line-height: 1.2;
}

.hero-intro p {
  max-width: 620px;
  margin: 0 auto;
  font-size: 18px;
  line-height: 1.5;
  text-align: left;
  padding-bottom: 30px;
}


.reach {
  padding: 60px 0 40px;
  background-image: url(http://image.desiringgod.org/careers-9s9zavaq-en/careers-9s9zavaq.jpg?0);
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-color: #f2f2f2;
  box-sizing: border-box;
  padding-bottom: 24px;
  background-size: contain;
}

.reach header {
  margin: 0 auto;
  max-width: 620px;
}

.reach header h3 {
  text-align: center;
  font-size: 23px;
  line-height: 1.5;
}

.reach header p {
  font-size: 18px;
  line-height: 1.5
}

.reach ul {
  display: flex;
  padding: 130px 0 240px;
  justify-content: center;
}

.reach ul li {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  background-color: #fff;
  margin: 0 50px;
  text-align: center;
}
</style>
