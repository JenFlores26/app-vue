<template>
    <div class="container">
        <div class="side-one">
            <h1>Hello!</h1>
            <p>Im Jennifer Flores</p>
            <p>I'am a Web Developer based in the San Diego</p>
            <button>Show More</button>
        </div>
        <div class="side-two">
            <img src="../assets/photos/PersonalWeb.png" alt="">
        </div>
    </div>
    <div class="about-me">
        <h1>About Me</h1>
        <div class="pic">
            <img src="../assets/photos/PersonalWeb.png" alt="">
            <div class="params">
            <p>Typically, I am creature of routine daily, habits. just to make it organize to function well...</p><hr>
            <p>Hi, I'am Jennifer Flores and I am so excited to be here today. I am a passionate programmer and technology enthusiast. I have been programming for over five years now and I absolutely love it.</p>
            <p>I specialize in JavaScript frameworks, such as React, Angular, and Node.js. I am also familiar with HTML, CSS, and other web development technologies. I am constantly learning new technologies and frameworks to stay up to date with the ever-changing world of programming.</p>
            <p>I believe that programming is an art form, and I strive to create beautiful, functional, and efficient code. I am passionate about creating applications that are user-friendly and intuitive. I also enjoy working with teams to create innovative solutions to complex problems.</p>
            <!--<p>I have a Bachelor's degree in Computer Science from the University of California, Berkeley. During my time at Berkeley, I was able to gain valuable experience in software engineering, web development, and database design. I also had the opportunity to work on several projects with other students and faculty members.</p>-->
            <p>I am currently working as a software engineer at a startup in San Francisco. I am responsible for developing new features and maintaining existing applications. I am also responsible for ensuring that our applications are secure and performant.</p>
            <p>I am passionate about learning new technologies and frameworks, and I am always looking for ways to improve my skills. I attend conferences, read books, and take online courses to stay up to date with the latest trends in programming.</p>
            <!--<p>I am also passionate about teaching others how to code. I have taught several coding classes at local libraries and community centers. I believe that everyone should have the opportunity to learn how to code, regardless of their background or experience level.</p>-->
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HomeVue',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container{
    margin: 0px 0px 0px 60px;
    padding: 0px 0px 0px 30px;
    /*border: 1px solid red;*/
    height: 85%;
    width: 90%;
    display: flex;
    text-align: left;
    align-items: flex-end;
    justify-content: left;

    .side-one{
        margin-bottom: 10%;
        line-height: 30px;
        h1{
            color:#558E96;
            font-size: 40px;
            font-family: 'Open Sans', 'Inter', sans-serif;
        }

        p{
            color: black;
            font-size: 20px;
        }

        button{
            border: none;
            background-color: #558E96;
            width: 9rem;
            height: 2.5rem;
            border-radius: 15px;
            color: #fff;
            font-size: 14px;
        }
    }

    .side-two{
        /*border: 1px solid red;*/
        padding-left: 200px;
        img{
            height: 600px;
            width: 500px;
        }
    }
}
.about-me{
    height: 85%;
    background-color: #FFD6C9;
    
    h1{
        padding-top: 85px;
        margin-left: 150px;
        text-align: left;
        color: #558E96;
        font-family: 'Open Sans', sans-serif;
        font-size: 40px;
    }
    .pic{
        display: flex;
        width: 1200px;
        height: 400px;
        margin: 0 100px 0 100px;
        /*border: 1px solid red;*/
        justify-content: center;

        img{
            margin: 70px 30px 30px 30px;
            border: 1px solid #558E96;
            padding: 10px;
            height: 200px;
            width: 170px;
        }
        .params{
            margin: 30px;
            /*border: 1px solid #558E96;*/
            padding: 10px;
            text-align: left;
            color: black;

            p{
                margin: 10px 0 10px 0;
            }
            hr{
                margin: 18px 0 18px 0;
            }
        }
    }
}
h3 {
    margin: 40px 0 0;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
a {
    color: #42b983;
}
</style>
