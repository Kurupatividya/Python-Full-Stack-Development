# Python-Full-Stack-Development
<!DOCTYPE html>
<html lang='en'>
  <head>
    <meta charset="utf-8">
    <meta name="viewpoint" content="width=device-width">
    <title>Basic HTML</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <main>
      <nav class='navBar'>
        <h1>SrividyaKurupati Portfolio</h1>
          <div class= 'navigationMenu'>
            <a href='#aboutMe'>About Me</a>
            <a href='#Skills'>Skills</a>
            <a href='#projects'>Projects</a>
            <a href='#contactForm'>Let's Connect!</a>
          </div>
         </nav>
      <section class='heroSection'>
        <img clss='profileImage'
        src='https://cdn-icons-png.flaticon.com/512/194/194938.png'>
        <div class='herosectionDetails'>
        <h1>Srividya Kurupati</h1>
        <h3>Computer Science Engineering</h3>
        </div>
      </section>
      <section class='aboutMe' id='aboutMe'>
        <h1>What I Do...</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut commodo diam augue, et dictum nisl hendrerit ac. Mauris dui ligula, ultricies in elementum ac, congue id odio. Aenean eget vehicula massa. Etiam sed massa vel sem tempus scelerisque eget vitae nibh. Aliquam eu lacinia purus. In mollis, erat nec vulputate convallis, tellus nunc molestie neque, ut mattis elit libero vulputate est. Vestibulum nec malesuada augue, tempus ullamcorper odio. Vivamus eu odio in ligula faucibus commodo in tincidunt ipsum. Cras aliquet consectetur est, eget tristique nibh posuere non. Aenean efficitur, magna sit amet iaculis bibendum, ex erat egestas massa, eu volutpat lectus eros sit amet massa. Nulla egestas turpis eget dui viverra, nec imperdiet quam sollicitudin. Vestibulum erat lectus, luctus sit amet massa vitae, sagittis dictum sapien. Ut faucibus, elit in placerat aliquam, arcu mi consequat nunc, quis scelerisque lectus urna tristique purus. Maecenas a nulla venenatis risus convallis vulputate sit amet ut turpis. Donec ullamcorper ligula sit amet leo porttitor, id pellentesque enim molestie.
        </p>
      </section>
      <section class='skillsAndProjects'>
        <div class='skills' id=skills>
          <h1 class='cardHeading'>Skills</h1>
          <img src='/images/html.svg' title='HTML'>
          <img src='/images/css.svg' title='CSS'>
          <img src='/images/javascript.svg' title='Javascript'>
          <img src='/images/node.svg' title='Node.JS'>
          <img src='/images/react.svg' title='React'>
          <img src='/images/mongodb.svg' title='MongoDB'>
          <img src='/images/firebase.svg' title='firebase'>
          <img src='/images/redux.svg' title='Redux'>
        </div>
        <div class='projects' id='projects'>
          <h1 class='cardHeading'>Projects</h1>
          <div class='projectContainer'>
            <img src='/images/css.svg'>
            <div class='projectDescription'>
              <h4>Project Name</h4>
              <p>Some details of the project.Some details of the project.Some details about the project.</p>
          </div>
        </div>
           
           <div class='projectContainer'>
            <img src='/images/css.svg'>
            <div class='projectDescription'>
              <h4>Project Name</h4>
              <p>Some details of the project.</p>
          </div>
        </div>
      </section>
      <section class='contactForm' id='contactForm'>
        <h1>Let's Connect!</h2>
        <div class='formGroup'>
          <label for='name'>Enter Full Name</label><br/>
          <input type='text' id='name' placeholder='Full Name'/>
        </div>
        <div class='formGroup'>
          <label for='email'>Email</label><br/>
          <input type='text' id='email' placeholder='Email' />
        </div>
        <div class='formGroup'>
          <label for='message'>Message</label><br/>
          <textarea placeholder="Send some message!" id="message" name="w3review"
            rows="4" cols="50"></textarea>
        </div>
        <button class='submitButton' onClick={submit()}>Connect</button>
      </section>
      
    </main>
    </body>
</html>
