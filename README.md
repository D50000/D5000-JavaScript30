# JavaScript mini projects
How to learn JavaScript ? There are lots of useful example here. Check it below!!
reference: https://wesbos.com/

# 1.Drum Kit
	Use web to simulate the Drum Kit.Add listener on "keydown" and play the sound.

# 2.Clock
	Use css and js to create a clock.
	
	ps:
	js method: new Date();
	CSS transition: transform 2s;
	
# 3.Update CSS Variables with JS
	User can dynamic controll the CSS,and it will change it immediately.
	
	ps:
	:root {
            --base: #592349;
            --spacing: 10px;
            --blur: 2px;
        }
		
	img {
            padding: var(--spacing);
            background: var(--base);
            filter: blur(var(--blur));
        }
	
	document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix);
	
# 4.Array practices I
	Some useful Array methods.
	
	ps:
	Array.filter()
	Array.map()
	Array.sort()
	Array.reduce()
	
# 5.Flex Panel Gallery
	Design a fancy gallery,it has many steps of animation.
	
	ps:
	addEventListener('click', togglefunction);
	CSS transition: transform 2s;
	
# 6.A searching bar
	Search for the input text,and highlighting the result text.
	
	ps:
	array.filter => match(RegExp(text, 'gi'));
	return replace(regex, `<span class="hl">${this.value}</span>`);
	join('');
	
# 7.Array practices II
	Some useful Array methods.
	
	ps:
	Array.some()
	Array.every()
	Array.find()
	Array.findIndex()
	Array.splice()
	
# 8.HTML5 Canvas
	Use the Canvas to draw on web.
	
	ps:
	ctx.moveTo(lastX, lastY);
    ctx.lineTo(e.offsetX, e.offsetY);
    ctx.stroke();

ps:canvas notes
https://www.html5canvastutorials.com/tutorials/html5-canvas-images/
http://entropymine.com/resamplescope/notes/browsers/

# 9.Log methods
    Some useful log methods.

    ps:
    console.log
    console.dir
    console.warn
    console.error
    console.info
    console.count
    console.table
    console.clear

# 10.Checkboxes Hold Shift function
    Checkboxes functions practices.

    ps:
    checkboxes.forEach(checkbox => checkbox.addEventListener('click', handleCheck));
    if (e.shiftKey && this.checked){loop the checkboxes and check the result}

# 11.Custom Video Player
    Change the Video Player UI.

    ps:
    Get Elements,addEventListener
    toggle.button

# 12.Key Sequence Detection
    Website will detect the secret input password.

    ps:
    window.addEventListener('keyup', (e) => 
    push() the element to the array and check it for answer.

# 13.Slide in on Scroll
    Images will slide in when the scroll moves.

    ps:
    dectect the scroll bar position and add the images animation
    window.addEventListener('scroll', debounce(checkSlide));
    (window.scrollY)
    sliderImage.classList.add('active');

# 14.JavaScript References
    JS References (simple "=" to other variable) VS copy (copy array to a new array).What's the different.

    ps:
    When you update the array-copy,you will also update the 
    original array.Array and Object will reference back.

    ps:
	For Array:
    1.use es6 Spread mesthod
    const team4 = [...players];
	
	2.use players.slice() to actually copy.
	
	3.use empty array to concat. 
	[].concat(players);
	
	For Object:
	1. const x = Object.assign({}, person, { number: 99});
	
	2. const x2 = {...person}; 
	
	3. const dev = Object.assign({}, wes);
	//Not support second layer deep properties.
	
	4. const dev2 = JSON.parse(JSON.stringify(wes));
	//Not recommend. It destroyed the object reference.
	
# 15.Local Storage
    It can save the user data in the local browser.

    ps:
    items.push(item); //push to array
    localStorage.setItem('items', JSON.stringify(items));

# 16.Mouse Move Shadow
    Image shadow will react with the mouse move.

    ps:
    addEventListener('mousemove', shadow);
    function shadow(e) {
    let { offsetX: x, offsetY: y } = e;
    ......

# 17.Sort without Articles
    Sort the word.

    ps:
    function strip(bandName) {
        return bandName.replace(/^(a |the |an )/i, '').trim();
    }
    const sortedBands = bands.sort((a, b) => strip(a) > strip(b) ? 1 : -1);

# 18.Adding Up Times with reduce
    Use reduce to sum the data in the elements.

    ps:
    const seconds = timeNodes
        .map(node => node.dataset.time)
        .map(timeCode => {
      const [mins, secs] = timeCode.split(':').map(parseFloat);
      return (mins * 60) + secs;
    })
    .reduce((total, vidSeconds) => total + vidSeconds);

# 19.Webcam fun
    Server Real Time Camera.

# 20.Speech Detection
    Use the computer Microphone. 

# 21.Geolocation
    Use GPS to locate the position.

# 22.Follow Along Link
    Fashion dynamic Highlighter.

    ps:
    add the addEventListener for the button.
    this.getBoundingClientRect();  //get information of user react
    change the css for the highlighter

# 23.Speech Synthesis
    A speecher that can control the speed and pitch.

    ps:
    import speech API
    const msg = new SpeechSynthesisUtterance();
    speechSynthesis.speak(msg);

# 24.Sticky Navigation
    Fashion sticky navigation.

    ps:
    window.addEventListener('scroll', fixNav);
    function fixNav() {
      if(window.scrollY >= topOfNav) {
        document.body.style.paddingTop = nav.offsetHeight + 'px';
        document.body.classList.add('fixed-nav');
      } else {
        document.body.classList.remove('fixed-nav');
        document.body.style.paddingTop = 0;
      }
    }

# 25.Event Capture, Propagation, Bubbling and Once.
    What's the difference between these.
    
    ps:
    Bubbling: Click the element and it will target through inner to outer tag, just like a bubble floating up.
    
    divs.forEach(div => div.addEventListener('click', logText, {
        capture: ture, // 預設為false
    }));

    capture: just target the outer container.
    Propagation:  e.stopPropagation(); //will just target the exactly what you click.

    button.addEventListener('click', () => {
        console.log('Click!!!');
    }, {
        once: true  //It just execute once, and will unbind the event.
    });

# 26.Stripe Follow Along Navigation
    Fashion dynamic Highlighter Navigation.

    ps:
    addEventListener for the triggers.
    getBoundingClientRect(); //get the x,y position
    change the Dom and animation.

# 27.Click and Drag
    Fashion dynamic menu.

    ps:
    addEventListener for the menu
    change the x,y and the classList of the Dom

# 28.Video Speed Controller
    A button that control the video play speed.

    ps:
    speed.addEventListener('mousemove', handleMove);
    video.playbackRate;  //transform the speed bar x.y value

# 29.Countdown Timer
    A simple countdown timer.

    ps:
    declare the UI timerDisplay

    countdown = setInterval(() => {
        const secondsLeft = Math.round((then - Date.now()) / 1000);
        // check if we should stop it!
        if(secondsLeft < 0) {
            clearInterval(countdown);
            return;
        }
        // display it
        displayTimeLeft(secondsLeft);
    }, 1000);

# 30.Whack a Mole
    A simple Whack a Mole game.

    ps:
    moles.forEach(mole => mole.addEventListener('click', bonk));
    
    function bonk(e) {
        if(!e.isTrusted) return; // cheater!
        score++;
        this.parentNode.classList.remove('up');
        scoreBoard.textContent = score;
    }







