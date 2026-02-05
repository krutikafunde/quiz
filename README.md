else if (step === 5) {
  if (currentScore < 2) {
    alert("Oops 😜 Try again, you can do better!");
    currentScore = 0;
    nextQuestion(1);
    return;
  }
