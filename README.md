[# login this is a login website]

https://www.youtube.com/watch?v=pUktm5BIbL8&ab_channel=Brookli
https://www.youtube.com/watch?v=b2Z0t40JXPA

https://www.google.com/sheets/about/
https://sheetdb.io/apis
https://www.w3schools.com/howto/howto_css_signup_form.asp


  <script>
        var form = document.getElementById('sheetdb-form');
    form.addEventListener("submit", e => {
      e.preventDefault();
      fetch(form.action, {
          method : "POST",
          body: new FormData(document.getElementById("sheetdb-form")),
      }).then(
          response => response.json()
      ).then((html) => {
        // you can put any JS code here
        window.open('message.html', '_blank');

      });
    });
    </script>




our google sheet
https://docs.google.com/spreadsheets/d/1g16HPeeEUOrsaf5SyB2IqSb0KEzRSApcyb7xJMSwoas/edit#gid=0
our website
https://earnestmd.github.io/login/)
