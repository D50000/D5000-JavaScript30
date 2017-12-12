JavaScript mini project

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
	