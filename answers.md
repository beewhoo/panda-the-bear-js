1) var profileImage = document.querySelector('img.profile-image').src='https://i.imgur.com/LE2Lzay.jpg';

1.2) var sky = document.querySelector("#left-image > img"); sky.src ='https://i.imgur.com/5G9FGVD.jpg';

2) var fullName = document.querySelector('h1.highlight').innerHTML = 'Bibek Thapa';

3) var employment = document.querySelector("#employment > h3"); employment.innerHTML = 'Experience';

4) var newBody = document.body; newBody.style.color='#D3D3D3';

5  var newHighlight = document.querySelector('.highlight');

    for (var i = 0; i < newHighlight.length; i++){
    newHighlight[i].style.color ='pink';
  }
