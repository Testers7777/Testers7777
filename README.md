<pre>
while (isAlive) {
	wakeUp();
	pray();
	eat("eggs");
	if (isWeekDay) {
		school();
	} else {
		code();
	}
	pray();
	eat();
	if (isBoxeDay) {
		boxe();
	} else {
		lift();
	}
	pray();
	eat();
	if (isWeekDay ?? new Date().getDay() == "Sunday") {
		homeworks();
	} else {
		play();
	}
	pray();
	sleep();
	repeat();
}
</pre>
