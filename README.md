# F1-Rookie

/* ===============================
   F1 ROOKIE QUIZ - FINAL STYLE
   =============================== */

/* Her ændrer vi fonten på hele quizzen.
   Vi bruger vores Formula 1-font for at få quizzen
   til at passe bedre ind i F1 Rookie-designet. */
.qsm-quiz-container,
.qmn_quiz_container,
.qsm-quiz-container *,
.qmn_quiz_container * {
  font-family: "Formula 1 Regular", sans-serif !important;
}

/* Styling af quiz-titlen.
   Overskriften bliver grøn, stor og med uppercase,
   så den matcher F1-universet og skaber mere fokus. */
.entry-title,
.qsm-quiz-container h1,
.qmn_quiz_container h1 {
  font-family: "Formula 1 Wide", sans-serif !important;
  color: #00e676 !important;
  text-transform: uppercase !important;
}

/* Her styles selve spørgsmålene i quizzen.
   Vi gjorde dem grønne og større, så de er lettere at læse
   og mere tydelige for brugeren. */
.qsm-quiz-container .quiz_section > p:first-of-type,
.qmn_quiz_container .quiz_section > p:first-of-type,
.qsm-quiz-container .quiz_section > span:first-of-type,
.qmn_quiz_container .quiz_section > span:first-of-type,
.qsm-quiz-container .mlw_qmn_question,
.qmn_quiz_container .mlw_qmn_question,
.qsm-quiz-container .qsm-question-wrapper,
.qmn_quiz_container .qsm-question-wrapper {
  color: #00e676 !important;
  font-family: "Formula 1 Wide", "Formula 1 Bold", sans-serif !important;
  font-size: 20px !important;
  line-height: 1.5 !important;
  margin-bottom: 24px !important;
}

/* Hvis spørgsmålet er skrevet som bold/strong,
   sørger vi også for, at det får samme grønne styling. */
.qsm-quiz-container .quiz_section p:first-of-type strong,
.qmn_quiz_container .quiz_section p:first-of-type strong,
.qsm-quiz-container .quiz_section strong:first-child,
.qmn_quiz_container .quiz_section strong:first-child {
  color: #00e676 !important;
  font-family: "Formula 1 Wide", "Formula 1 Bold", sans-serif !important;
}

/* Her styles svarmulighederne.
   Vi gjorde teksten hvid for at skabe kontrast
   til den mørke baggrund og gøre teksten mere læsbar. */
.qsm-quiz-container label,
.qmn_quiz_container label,
.qsm-quiz-container label *,
.qmn_quiz_container label *,
.qsm-quiz-container .qmn_radio_answers,
.qmn_quiz_container .qmn_radio_answers,
.qsm-quiz-container .qmn_radio_answers *,
.qmn_quiz_container .qmn_radio_answers *,
.qsm-quiz-container .mlw_qmn_question_answer,
.qmn_quiz_container .mlw_qmn_question_answer,
.qsm-quiz-container .mlw_qmn_question_answer *,
.qmn_quiz_container .mlw_qmn_question_answer * {
  color: #f5f7fa !important;
  font-family: "Formula 1 Regular", sans-serif !important;
  font-size: 17px !important;
  line-height: 1.7 !important;
}

/* Her ændrer vi radio buttons til grønne.
   Det hjælper med at skabe en mere ensartet visuel stil
   gennem hele quizzen. */
.qsm-quiz-container input[type="radio"],
.qmn_quiz_container input[type="radio"] {
  accent-color: #00e676 !important;
}

/* Mere afstand mellem spørgsmålene.
   Det gør quizzen mere overskuelig og lettere at læse. */
.qsm-quiz-container .quiz_section,
.qmn_quiz_container .quiz_section {
  margin-bottom: 55px !important;
}

/* Styling af quiz-knapper.
   Vi bruger gul CTA-farve for at gøre knapperne
   tydelige og nemme at finde for brugeren. */
.qsm-quiz-container .qmn_btn,
.qmn_quiz_container .qmn_btn,
.qsm-quiz-container button,
.qmn_quiz_container button,
.qsm-quiz-container input[type="submit"],
.qmn_quiz_container input[type="submit"],
.qsm-btn,
.mlw_qmn_quiz_link,
a.qmn_btn {
  background-color: #ffe45e !important;
  color: #0b0f14 !important;
  border: 2px solid #ffe45e !important;
  font-family: "Formula 1 Bold", sans-serif !important;
  padding: 12px 26px !important;
  border-radius: 4px !important;
  text-decoration: none !important;
}

/* Hover-effekt på knapper.
   Når brugeren holder musen over knappen,
   ændrer den udseende for at gøre siden mere interaktiv. */
.qsm-quiz-container .qmn_btn:hover,
.qmn_quiz_container .qmn_btn:hover,
.qsm-quiz-container button:hover,
.qmn_quiz_container button:hover,
.qsm-quiz-container input[type="submit"]:hover,
.qmn_quiz_container input[type="submit"]:hover,
.qsm-btn:hover,
.mlw_qmn_quiz_link:hover,
a.qmn_btn:hover {
  background-color: transparent !important;
  color: #ffe45e !important;
  border-color: #ffe45e !important;
}

/* Her skjuler vi kommentar-sektioner.
   De var ikke relevante for quiz-siderne
   og gjorde layoutet mere rodet. */
.comments-area,
#comments,
.comment-respond,
#respond,
.ast-comment-formwrap,
.ast-comments-area,
.comment-form {
  display: none !important;
}

/* Vi fjernede next/previous navigation,
   fordi brugeren ikke skulle videre mellem blogposts.
   Det gjorde quiz-siderne mere simple og overskuelige. */
.post-navigation,
.nav-links,
.single .navigation,
.navigation.post-navigation,
.ast-single-post-navigation,
.ast-post-navigation,
.nav-previous,
.nav-next {
  display: none !important;
}

/* Sticky header betyder, at menuen bliver
   øverst på siden, når brugeren scroller.
   Det gør navigationen hurtigere og mere brugervenlig. */
.site-header {
  position: sticky;
  top: 0;
  z-index: 9999;
  background: #050b10;
}
