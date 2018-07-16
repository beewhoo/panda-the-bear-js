1) var profileImage = document.querySelector('img.profile-image').src='https://i.imgur.com/LE2Lzay.jpg';

1) var sky = document.querySelector("#left-image > img"); sky.src ='https://i.imgur.com/5G9FGVD.jpg';

2) var fullName = document.querySelector('h1.highlight').innerHTML = 'Bibek Thapa';

3) var employment = document.querySelector("#employment > h3"); employment.innerHTML = 'Experience';

4) var newBody = document.body; newBody.style.color='#D3D3D3';

5)  var newHighlight = document.querySelector('.highlight');
    for (var i = 0; i < newHighlight.length; i++){
    newHighlight[i].style.color ='pink';
  }
  
6) var font = document.body.style.fontFamily = 'monospace';

7)var icons = document.querySelectorAll('.action-icon-bg');
  icons.forEach(function(icon) { icon.style.backgroundColor = "black" } );
  
8)var nameContactForm = document.querySelector('#name'); nameContactForm.placeholder = 'identify yourself';

9) var newMessageForm = document.querySelector('#message'); newMessageForm.placeholder = 'state your business';

10) var nameValue = document.querySelector('#name'); nameValue.value = 'your nemesis';

11) var newValueEmail = document.querySelector('#email'); newValueEmail.value = "koalathebear@gmail.com";
    
12) var submitButton = document.querySelector('form #submit'); submitButton.value = "En garde!";

13)var submitButton = document.querySelector('form #submit'); submitButton.disabled = true;

14) var personalInfo = document.querySelector('.bio-info'); personalInfo.innerHTML = "";
    
