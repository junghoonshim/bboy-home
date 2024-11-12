<script>
  // @ts-nocheck
  
    import Header from './Header.svelte';
    import Footer from './Footer.svelte';
  </script>
  
  <Header />
  
  <main class="container">
    <h2>최고의 무대를 선사하겠습니다.</h2>
    <div class="contact">
      <figure class="map">
        <!-- svelte-ignore a11y-missing-attribute -->
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3260.577373565608!2d126.83134381177766!3d35.19208475657479!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x35718ee64eb37b97%3A0xb53095bd668db6b0!2z7Iug7LC967aA7JiBMuywqOyVhO2MjO2KuA!5e0!3m2!1sko!2skr!4v1731417643673!5m2!1sko!2skr" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      </figure>
      <address>
        <p>202동 1303호<br>미쯔 스튜디오</p>
            <p>Email: 
          <a href="mailto:bbrother@gmail.com">bbrother@gmail.com</a></p>
            <p>Tel: 
                <a href="tel:010-5459-****">010-5453-****</a> / 
          <a href="tel:010-000-0000">010-000-0000</a>
               </p>
            <p>Fax: 031-000-0000</p>
      </address>
    </div>
  </main>
  
  <Footer />
  
  <style lang="scss">
    .contact {
      display: flex;
      gap: 75px;
      figure, address { width: 50%; }
      address { 
        font-style: normal; 
        p:not(:first-child) { margin-bottom: 5px; }
      }
      a { color: inherit; }
    }
  
    .container {
      background: #fff;
    }
  </style>