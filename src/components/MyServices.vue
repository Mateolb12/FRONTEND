<template>
    <div id="services">
        <section class="about-us">
            <div class="contenedor1">
                <h2 class="titulo">We provide a wide range</h2>
                <div class="contenedor-articulo">
                    <div class="articulo" data-aos="zoom-in-right">
                        <b-icon class="b-icon" icon="vector-pen"></b-icon>
                        <h3>Graphic design</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla accusamus reiciendis ab maxime animi alias ipsam ex debitis dolor provident!</p>
                        <a href="#">Read more ---></a>
                    </div>
        
                    <div class="articulo" data-aos="zoom-in-right" >
                        <b-icon class="b-icon" icon="code"></b-icon>
                        <h3>Web design</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla accusamus reiciendis ab maxime animi alias ipsam ex debitis dolor provident!</p>
                        <a href="#">Read more ---></a>
                    </div>

                    <div class="articulo" data-aos="zoom-in-right" >
                        <b-icon class="b-icon" icon="gear-fill"></b-icon>
                        <h3>Video production</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla accusamus reiciendis ab maxime animi alias ipsam ex debitis dolor provident!</p>
                        <a href="#">Read more ---></a>
                    </div>

                    <div class="articulo" data-aos="zoom-in-right" >
                        <b-icon class="b-icon" icon="bar-chart-fill"></b-icon>
                        <h3>SEO</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla accusamus reiciendis ab maxime animi alias ipsam ex debitis dolor provident!</p>
                        <a href="#">Read more ---></a>
                    </div>

                    <div class="articulo" data-aos="zoom-in-right" >
                        <b-icon class="b-icon" icon="pie-chart-fill"></b-icon>
                        <h3>Digital Marketing</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla accusamus reiciendis ab maxime animi alias ipsam ex debitis dolor provident!</p>
                        <a href="#">Read more ---></a>
                    </div>

                    <div class="articulo" data-aos="zoom-in-right" >
                        <b-icon class="b-icon" icon="chat-fill"></b-icon>
                        <h3>Inphografics</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla accusamus reiciendis ab maxime animi alias ipsam ex debitis dolor provident!</p>
                        <a href="#">Read more ---></a>
                    </div>
                </div>         
            </div>
        </section>
    </div>
</template>


<style scoped>
*{
  --dark-blue: #1d273b;
  --middle-blue: #2570ff;
  --light-blue: #5D6678;
  --purple-blue: #667db6;
  --gray:#adb6c7;
  --light-green: #1FDE82;
  --white: #fff;
  --light-gray: #f2f2f2;
  --white-gray: #f2f5fc;

}

h1,
h2,
h3,
h4,
h5,
h6 {
  color: var(--dark-blue);
  font-weight: 300;
}

.contenedor1 {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  overflow: hidden;
  padding: 60px 0;
}

h1 {
  font-size: 50px;
}

.titulo {
  font-size: 50px;
}

.about-us {
  background: var(--light-gray);
}

.contenedor-articulo {
  display: flex;
  flex-wrap: wrap;
  margin-top: 60px;
  justify-content: space-around;
}

.articulo {
  width: 29%;
  background: var(--white);
  margin-bottom: 30px;
  border-radius: 10px;
  padding: 45px 30px 60px 30px;
  transition: 0.5s;
}

.articulo:hover {
  box-shadow: 0 4px 10px rgba(17, 29, 48, 0.26);
}

.articulo > .b-icon {
  font-size: 30px;
  color: var(--white);
  background: var(--light-green);
  display: inline-block;
  width: 70px;
  height: 70px;
  text-align: center;
  padding: 10px;
  border-radius: 50%;
  box-shadow: 0 8px 32px rgba(31, 222, 130, 0.46);
}

.articulo > h3 {
  font-size: 24px;
  margin-top: 30px;
}

.articulo > p {
  font-weight: 100;
  color: var(--light-blue);
  margin-top: 15px;
  padding-bottom: 20px;
}

.articulo > a {
  color: var(--light-blue);
  font-weight: 400;
  text-decoration: none;
}

.articulo > a:hover {
  color: var(--light-green);
  transition: color 0.5s;
}
</style>



