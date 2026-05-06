### 📇 Contact

Je maîtrise le français et l'anglais. N'hésitez pas à entrer en contact dans
l'une ou l'autre de ces langues!

marc-andre.belanger [-at-] umontreal.ca.

### 🎓 Education
- **B. Sc. in Chemistry**, Université de Montréal
- **M. Sc. in Computer Science**, Université de Montréal (ongoing)

### 📄 Publications
- [Marc-André Bélanger and Marc Feeley, **A Foreign Function Interface between Gambit Scheme and CPython**. In _Scheme Workshop (SW'22)_, September 2022. (pre-print)](https://andykeep.com/SchemeWorkshop2022/scheme2022-final22.pdf)
- [Marc-André Bélanger and Marc Feeley, **A Scheme Foreign Function Interface to JavaScript Based on an Infix Extension**. In _European Lisp Symposium (ELS'21)_, May 2021.](https://zenodo.org/record/4711424)
- [Ernzerhof, Matthias, M. Bélanger, Didier Mayou and Tahereh Nemati Aram. **Simple model of a coherent molecular photocell.** _The Journal of chemical physics_ 144 13 (2016): 134102 .](https://hal.archives-ouvertes.fr/hal-01620569/file/Matthias%20JCP%20-%20copie.pdf)

### 🗣️ Conferences
- [Marc-André Bélanger and Marc Feeley, **Interfacing with CPython from Gambit Scheme**. In _1st Languages, Architectures, and Tools for Heterogeneous Computing (LATHC) Workshop 2023_, Februrary 2023](https://jnamaral.github.io/LATHC/program/#INTERFACING)
- [Marc-André Bélanger and Marc Feeley, **A lightweight approach for accessing Python modules from Gambit Scheme (Lightning Talk)**. In _Scheme and Functional Programming Workshop (SFPW'21)_, August 2021.](https://icfp21.sigplan.org/details/scheme-2021-papers/9/A-lightweight-approach-for-accessing-Python-modules-from-Gambit-Scheme-Lightning-Tal)

### 🛠️ Experience

- **2025-2026** | CTO - BIASafe AI
  
 Directed the end-to-end technical strategy, architecture, and engineering
 execution for an AI-focused FinTech startup. I led the organization from
 **zero-to-one** under the business and technical constraints and objectives set by
 management. I established SDLC best practices for a team of 6 developers, owned
 the security posture, fully leveraged modern **agentic coding** practices, built all
 of the data pipelines, handled third-party contract work, etc. I designed,
 implemented and maintained:

  - A robust **distributed worker** execution model designed to provide exactly-once
    semantics through a hybrid message queue and durable queue architecture,
    best-effort optimistic messaging with retries and polling (**Docker Swarm, Celery,
    Redis, RabbitMQ, PostgreSQL**)
  - The infrastructure and codebase so that we could reach **SOC2 compliance**
  - **Resilient ETL pipelines** with clearly defined semantics and manual overrides
    along with full operational observability through dashboards
  - A **monorepo** structure that enabled quick onboarding and easy LLM integration
    for accelerating development
  - An easy to use development environment leveraging **devcontainers** and
    multi-layered docker images for quick and easy onboarding and experimentation
  - **Isomorphic development and cloud environments** where developers could run the
    whole platform on their machines as in staging and prod
  - Fully automated **CI/CD pipelines** with proper testing hierarchy, merge queue and
    early termination for faster turnaround
  - Strict stateful vs stateless separation at the application level to leverage
    cloud vendor data persistence for reliability while **avoiding vendor lock-in**
  - **Internal libraries** as building blocks to enforce "one way to do things" in the
    whole codebase, facilitate understanding, simplify adding new features,
    enforcing the execution model semantics and other requirements at the library
    level
  - Enforced **Pydantic** typing both for everything from configuration to function
    signatures
  - Compiling Pydantic types to TypeScript to **eliminate drift** between the back-end
    and the front-end
  - **Traceable provenance** and genealogy for every single data artifact that went
    through the system, from SFTP files to API requests with replayability for
    auditing (PostgreSQL and SQLModel)
  - **Point-in-time and provenance guarantees** at the database schema level to enable
    reproducible backtests and auditing (**ClickHouse** and PostgreSQL)
  - Strict environment separation and secret handling between staging and
    production cloud developments on **GCP**
  - Strictly IaC-only versioned infrastructure with **Terraform**
  - Monitoring built-in at the library and infrastructure level with **Grafana** and
    **Prometheus**
  - Optimized backtesting code reducing resource usage and time by between **30% to
    300%**.
  - Leveraged Cloud Run for **elastic computing** availability when launching backtests
  - Managed PhD interns working on chatbot, **RAG** and completion pipelines


- **2022–2025** | Software consultant
  
  Worked on various contracts for clients involving web application development,
  web scraping, consulting, API reverse-engineering, data collection, analysis, and
  sanitization for SMBs.

- **2024** | LLM Optimization Lead – DeepStructure
  
  Worked as an R&D contractor for a generative AI PaaS on LLM-based workflow
  optimization and evaluation. Full-stack involvement from cutting-edge prompt
  engineering to computation graph optimizations to JITing prompt optimizers using
  meta-prompting agentic techniques with DSPy and TextGrad.

- **2023–2024** | Lecturer – Université de Montréal
  
  I taught two introductory programming courses to hundreds of students. The
  course uses Python and the codeBoot environment, which I help build and
  maintain. I managed around 15 TAs for grading, assignment and lab hours. My teaching was highly rated by students.

- **2014–2023** | Software Developer and Consultant – Imagerie des Pionniers
  
  Built business-critical internal and customer-facing full-stack web apps for
  cloud and on-premise deployments. Acted as a consultant for stakeholders and
  decision-makers for procurement, strategy and litigation.

  I have built and maintained:

  - A web-based appointment scheduler for patients handling over 20 000 appointments a year
  - An SMS-based waiting room management system to contact patients just-in-time for their exam handling hundreds of patients daily for over 100 000 business interactions per year
  - An issue tracking and ticketing system for internal use
  - A DICOM image sharing portal for practicioners and patients

- **2016** | Technical Support Specialist / Software Developer – La Presse
  
  Built Apple device monitoring and reporting system using Apple Profile
  Manager. Created dashboards for management and tech support using PowerBI.
  Provided general IT support in a high-volume media environment.

- **2013–2015** | Teaching Assistant – Université de Montréal
  
  I was a teaching assitant for multiple undergraduate chemistry courses (general
  chemistry, physical chemistry, inorganic chemistry). My work was highly rated by
  students and innovative for the time, providing extensive course notes,
  interactive presentations using electronics structure calculations and other
  software for the benefit of the students.

### ⚙️ A few projects

In no particular order or categorization.

- **[codeBoot](https://codeboot.org)** - Browser-based IDE for teaching programming

  One of the main contributors to the project. I have worked on every part of the
  project, from the front-end to the compiler to the backend services (cloud and on-prem).
  I have used codeBoot to teach introductory programming courses at Université de Montréal.

  See **pyinterp** below for details on the codeBoot Python <-> JavaScript FFI.
  
- **[jsrna](https://github.com/belmarca/jsrna)** – JavaScript RNA Base Pair Annotation
  
  Web-based RNA base-pair annotator/viewer written in JavaScript. Also created a novel annotation method using a ResNet-based transfer
  learning model. I reformulated base-pair annotation as a classification task (similar to MNIST) using a canonicalized projection method to create an *alphabet*.
  Novel, highly efficient and accurate method yet unpublished.

- **BLINX** - ESP32-based board for teaching programming

  I am a co-founder of the company that markets and sells the BLINX hardware
  and software. BLINX is a small board used for teaching programming. It can be
  plugged into a USB port and programmed from the codeBoot environment. It accepts
  a multitude of Grove sensors. I wrote a high-performance firmware proof-of-concept
  using ESP-IDF as part of our R&D.

- **py2js** – Python to JavaScript Compiler
  
  Wrote a compiler targeting a subset of Python 3. Used in production as part of
  the codeBoot project, a web-based Python IDE for teaching.

- **pyinterp** – CPS-Style Python Interpreter in Python
  
  Implemented the FFI layer as well as Python builtins, critical to codeBoot’s backend.
  The FFI integrates ideas from my research into a production system. The FFI allows
  users to seamlessly import and use JavaScript libraries from Python code. This requires
  careful grammar, tokenizer and parser extensions along with a well designed runtime
  to preserve the illusion of writing pure Python code.

  Try the FFI at https://codeboot.org by executing `\alert("Hello!")` at the REPL.

- **codeBoot on Microcontrollers**
  
  Implemented WebSerial communication between codeBoot and MicroPython. Migrated legacy
  development environments to Docker for higher reliability and reproducibility. Handled
  firmware build automation. Deep Wireshark sessions to debug a microcontroller WebSocket implementation.

- **[Ribbit Scheme](https://github.com/udem-dlteam/ribbit)**

  Implemented the Ribbit VM in Haskell. Built classical source-to-source
  transformations (e.g., closure conversion) into the compiler. Bootstrapped an
  x86-64 backend. Worked on porting Racket’s “sets-of-scopes” expander to
  Ribbit.

- **[Gambit Scheme](https://github.com/gambit/gambit)**
  
  Extended Gambit’s infix reader for JavaScript and Python syntax. Built an
  interface between Gambit Scheme and CPython using the CPython C API. Built
  an interface between Gambit Scheme and JavaScript which you can try [here](https://try.gambitscheme.org) (write `\alert("Hello!")` at the REPL).

- **2023 DIRO Hackathon**
  
  Helped organize the Université de Montréal’s 2023 DIRO Hackathon.
  Participants built games using the codeBoot platform to run isomorphically on
  the browser and an ESP32-based board.

- **CLA** – Article Reading Club
  
  Organized a scientific article reading club for compiler and programming
  language theory groups. Also hosted a CTF for the group.

- **Ethereum transaction graph explorer**

  Back when these things were rare, I built an Ethereum transaction graph
  explorer using Neo4j. I used this to find evidence of wrongdoing in some
  personal investments.
  
- **Making EVM smart contracts lie**

  Wrote a PoC EVM smart contract on the **testnet** to exploit out-of-band
  problems on a major chain explorer which resulted in spoofed token metadata,
  misguiding potential investors.
