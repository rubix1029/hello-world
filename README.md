scramble = prompt('Input Scramble');
output = ""

// Step 1: Orient First Layer
	//First Corner

if( scramble.charAt(21) === 'y') {
	output += "";
}

else if( scramble.charAt(8) === 'y') {
	output += "R U R’ ";
scramble = scramble.charAt(3) + scramble.charAt(1) + scramble.charAt(16) + scramble.charAt(6) + scramble.charAt(11) + scramble.charAt(0) + scramble.charAt(5) + scramble.charAt(7) + scramble.charAt(13) + scramble.charAt(9) + scramble.charAt(10) + scramble.charAt(2) + scramble.charAt(12) + scramble.charAt(17) + scramble.charAt(14) + scramble.charAt(15) + scramble.charAt(4) + scramble.charAt(21) + scramble.charAt(18) + scramble.charAt(19) + scramble.charAt(20) + scramble.charAt(8) + scramble.charAt(22) + scramble.charAt(23); 
}

console.log(output);
