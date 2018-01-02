JavaScript mini projects

1.Drum Kit
	Use web to simulate the Drum Kit.Add listener on "keydown" and play the sound.

2.Clock
	Use css and js to create a clock.
	
	ps:
	js method: new Date();
	CSS transition: transform 2s;
	
3.Update CSS Variables with JS
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
	
4.Array practices I
	Some useful Array methods.
	
	ps:
	Array.filter()
	Array.map()
	Array.sort()
	Array.reduce()
	
5.Flex Panel Gallery
	Design a fancy gallery,it has many steps of animation.
	
	ps:
	addEventListener('click', togglefunction);
	CSS transition: transform 2s;
	
6.A searching bar
	Search for the input text,and highlighting the result text.
	
	ps:
	array.filter => match(RegExp(text, 'gi'));
	return replace(regex, `<span class="hl">${this.value}</span>`);
	join('');
	
7.Array practices II
	Some useful Array methods.
	
	ps:
	Array.some()
	Array.every()
	Array.find()
	Array.findIndex()
	Array.splice()
	
8.HTML5 Canvas
	Use the Canvas to draw on web.
	
	ps:
	ctx.moveTo(lastX, lastY);
    ctx.lineTo(e.offsetX, e.offsetY);
    ctx.stroke();

9.Log methods
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

10.Checkboxes Hold Shift function
    Checkboxes functions practices.

    ps:
    checkboxes.forEach(checkbox => checkbox.addEventListener('click', handleCheck));
    if (e.shiftKey && this.checked){loop the checkboxes and check the result}

11.Custom Video Player
    Change the Video Player UI.

    ps:
    Get Elements,addEventListener
    toggle.button

12.Key Sequence Detection
    Website will detect the secret input password.

    ps:
    window.addEventListener('keyup', (e) => 
    push() the element to the array and check it for answer.

13.Slide in on Scroll
    Images will slide in when the scroll moves.

    ps:
    dectect the scroll bar position and add the images animation
    window.addEventListener('scroll', debounce(checkSlide));
    (window.scrollY)
    sliderImage.classList.add('active');

14.JavaScript References
    JS References VS copy.What's the different.

    ps:
    When you update the array-copy,you will also update the 
    original array.Array and Object will reference back.

    ps:
    use es6 Spread mesthod
    const team4 = [...players];




