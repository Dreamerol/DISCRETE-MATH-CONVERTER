<h1 align="center">🔄 𝗡𝗙𝗔 → 𝗗𝗙𝗔 𝗖𝗢𝗡𝗩𝗘𝗥𝗧𝗘𝗥 – 𝗖++</h1>



<br>


---

<img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/8bc1f4f07b4a6f498d056d97281f015b731e6326/ZZZZZCALCULATOR777.png" alt="MATH" style="width:100%; height:auto;">



---





<br>

<br>

<br>










<div align="center">

<a href="https://github.com/Dreamerol/CARDFOLIO">

<img
src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/TECH-STACK-mihaela-koseva.png"
width="100%"
alt="Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Software Engineering, AI Engineer, Applied Machine Learning, Data Science, Software Engineer, Backend Engineer, REST APIs, Python, C++, Java, SQL, Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Software Engineer, Sofia, Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Sofia"
/>

</a>

</div>










<br>








<div align="center">

<table>
<tr>

<td align="center" width="12%">
<span style="font-size:1.55em;">🌐</span><br>
<span style="font-size:1.4em;"><a href="https://dreamerol.github.io/MIHAELA-KOSEVA-AI/">𝗪𝗘𝗕𝗦𝗜𝗧𝗘</a></span>
</td>

<td align="center"><span style="font-size:1.3em;">│</span></td>





<td align="center" width="12%">
<span style="font-size:1.55em;">⚛️</span><br>
<span style="font-size:1.4em;"><a href="https://github.com/Dreamerol/AI-BUILDS">𝗔𝗜𝗙𝗢𝗟𝗜𝗢</a></span>
</td>

<td align="center"><span style="font-size:1.3em;">│</span></td>






<td align="center" width="12%">
<span style="font-size:1.55em;">🟢</span><br>
<span style="font-size:1.4em;"><a href="https://github.com/Dreamerol/PORTFOLIO">𝗣𝗢𝗥𝗧𝗙𝗢𝗟𝗜𝗢</a></span>
</td>

<td align="center"><span style="font-size:1.3em;">│</span></td>

<td align="center" width="12%">
<span style="font-size:1.55em;">🧩</span><br>
<span style="font-size:1.4em;"><a href="https://github.com/Dreamerol/CARDFOLIO">𝗥𝗘𝗣𝗢𝗦</a></span>
</td>


<td align="center"><span style="font-size:1.3em;">│</span></td>

<td align="center" width="12%">
<span style="font-size:1.55em;">✅</span><br>
<span style="font-size:1.4em;"><a href="https://github.com/Dreamerol/RESUME">𝗥𝗘𝗦𝗨𝗠𝗘</a></span>
</td>



<td align="center"><span style="font-size:1.3em;">│</span></td>

<td align="center" width="12%">
<span style="font-size:1.55em;">🐙</span><br>
<span style="font-size:1.4em;"><a href="https://github.com/Dreamerol">𝗚𝗜𝗧𝗛𝗨𝗕</a></span>
</td>



<td align="center"><span style="font-size:1.3em;">│</span></td>

<td align="center" width="12%">
<span style="font-size:1.55em;">🔗</span><br>
<span style="font-size:1.4em;"><a href="https://www.linkedin.com/in/mihaela-koseva-software-engineer">𝗟𝗜𝗡𝗞𝗘𝗗𝗜𝗡</a></span>
</td>


<td align="center"><span style="font-size:1.3em;">│</span></td>

<td align="center" width="12%">
<span style="font-size:1.55em;">✉️</span><br>
<span style="font-size:1.4em;"><a href="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/MIHAELA_KOSEVA_VIZITKA.jpg">𝗖𝗢𝗡𝗧𝗔𝗖𝗧</a></span>
</td>

</tr>
</table>

</div>











---
















<br>



<h2>📖 Overview</h2>

This project implements a conversion from a Nondeterministic Finite Automaton (NFA) to a Deterministic Finite Automaton (DFA) using C++.

It combines theoretical concepts from automata theory with practical implementation, demonstrating how nondeterministic systems can be systematically transformed into deterministic ones using classes, sets, and data structures.

---

<h2>🚀 Purpose</h2>

The main objectives of this project are to:

Understand the difference between NFA and DFA
Implement the subset construction algorithm
Practice working with data structures and structured program design
Apply theoretical computer science concepts in practice

---

Applications include:

🖥️ Compilers
🔍 Lexical analyzers
🧩 Pattern recognition systems

---

<h2>🧠 Theory Overview</h2>

🔹 Nondeterministic Finite Automaton (NFA)

An NFA allows:

Multiple transitions for the same input symbol
Transitions to several states simultaneously

The next state is not uniquely determined.

🔹 Deterministic Finite Automaton (DFA)

A DFA ensures:

Each state has exactly one transition per input symbol
There is no ambiguity in transitions

DFAs are easier to simulate and implement.

---

<h2>⚙️ Algorithm Used</h2>

The conversion uses the subset construction algorithm, where:

Each DFA state represents a set of NFA states.

This eliminates nondeterminism by grouping all possible states into a single deterministic state.

Step-by-Step Summary (Emoji Style)

1️⃣ Initial State – Start with the NFA start state → First DFA state
2️⃣ State Expansion – For each DFA state, compute all reachable states for every input symbol
3️⃣ Avoid Duplicates – Reuse existing DFA states to ensure uniqueness
4️⃣ Final States – Mark DFA states as final if containing any NFA final state
5️⃣ Result – Fully deterministic DFA ready for simulation or analysis

---

<h2>💡 Key Insight</h2>

A DFA state is a set of NFA states.

This transformation removes nondeterminism and produces a deterministic automaton.

---

<h2>📌 Notes</h2>

Educational project focused on clarity and correctness
Advanced features like ε-transitions may be simplified
Emphasis on structured programming and algorithmic thinking

---

<h2>💡 Learning Outcomes</h2>

By completing this project, you will:

Understand NFA → DFA conversion
Implement theoretical algorithms in C++
Gain experience with sets, maps, and structured logic
Improve problem-solving and algorithmic thinking
Prepare a portfolio-ready, recruiter-friendly project

---

<h2>💼 Key Skills</h2>

* 🐍 **C++ Programming & OOP**
* 🧩 **Algorithm Implementation**
* 🗂️ **Data Structures:** sets, maps
* 🖥️ **Console Application Development**
* 🧠 **Problem-Solving & Logical Thinking**
* 📊 **Structured Program Design & Debugging**

---

<br><br>










<h2 align="center">⭐ Explore repos & star what you find interesting.</h2>















<div align="center">

<p style="font-size:10px; line-height:1.6; letter-spacing:0.2px;">

Mihaela Koseva (Михаела Косева) • Sofia University (Софийски университет) • AI Engineer • Software Engineer • Backend Engineer • Data Systems & APIs • Applied Machine Learning • Deep Learning • Neural Networks • Model Training • Data Pipelines • Data Science • LLMs • Python • C++ • Java • Clojure • SQL • PyTorch • TensorFlow • Scikit-learn • Pandas • NumPy • ETL • Data Modeling • MLOps
</p>

<p style="font-size:10px; opacity:0.7;">
© 2026 Mihaela Koseva (Михаела Косева) • Софийски университет • Original portfolio design.
</p>

<p style="font-size:10px; opacity:0.7;">
🔗 Explore on GitHub:
<a href="https://github.com/Dreamerol">Mihaela Koseva (Михаела Косева) • Software Engineer • AI • ML • Dreamerol</a>
</p>

</div>















<br><br><br>















<div align="center">

<a href="https://github.com/Dreamerol/CARDFOLIO">
  <img 
    src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/MIHAELA%20KOSEVA-DREAMEROL.png"
    width="100%"
    alt="Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Software Engineering, AI Engineer, Applied Machine Learning, Data Science, Software Engineer, Backend Engineer, REST APIs, Python, C++, Java, SQL"
  />
</a>

</div>















<br><br><br>







---








<table align="center" cellspacing="0" cellpadding="2">
<tr>

<td>
<a href="https://www.linkedin.com/in/mihaela-koseva-software-engineer" target="_blank">
<img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/Butoni%20LINKEDIN.png" height="130"
alt="Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Software Engineering, AI Engineer, Applied Machine Learning, Data Science, Software Engineer, Backend Engineer, REST APIs, Python, C++, Java, SQL">
</a>
</td>


<td>
<a href="https://github.com/Dreamerol" target="_blank">
<img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/Butoni%20GITHUB.png" height="130"
alt="Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Software Engineering, AI Engineer, Applied Machine Learning, Data Science, Software Engineer, Backend Engineer, REST APIs, Python, C++, Java, SQL">
</a>
</td>


<td>
<a href="https://github.com/Dreamerol/CARDFOLIO" target="_blank">
<img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/Butoni%20REPOSITORIES.png" height="130"
alt="Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Software Engineering, AI Engineer, Applied Machine Learning, Data Science, Software Engineer, Backend Engineer, REST APIs, Python, C++, Java, SQL">
</a>
</td>


<td>
<a href="https://github.com/Dreamerol/ALLSTATS" target="_blank">
<img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/Butoni%20STATS.png" height="130"
alt="Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Software Engineering, AI Engineer, Applied Machine Learning, Data Science, Software Engineer, Backend Engineer, REST APIs, Python, C++, Java, SQL">
</a>
</td>


<td>
<a href="https://github.com/Dreamerol/RESUME" target="_blank">
<img src="https://raw.githubusercontent.com/Dreamerol/Dreamerol/main/Butoni%20RESUME.png" height="130"
alt="Mihaela Koseva (Михаела Косева), Sofia University (Софийски университет), Software Engineering, AI Engineer, Applied Machine Learning, Data Science, Software Engineer, Backend Engineer, REST APIs, Python, C++, Java, SQL">
</a>
</td>

</tr>
</table>





<br><br><br><br><br>




