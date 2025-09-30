gsap.to([cordWrapper, ribbon], {
     opacity: ∅,
     duration: ∅.5,
     onComplete: () => {
       cordWrapper.style.display = "none";
       ribbon.style.display = "none";
     }
  });
