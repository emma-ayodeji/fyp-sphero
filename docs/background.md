Summary
This chapter details the research and technical foundations supporting this project. Section 2.1 reviews published literature on Computational Thinking (CT) education, Cognitive Load Theory, Constructionism, and relevant empirical findings. Section 2.2 describes the technical specifications of the hardware platforms (Sphero Indi and Sphero BOLT), the adaptation of PACT tasks, and the empirical measurement instruments (including the NASA-TLX workload framework).

2.1 Topic Material
Computational thinking is an essential problem solving skill that enables learners to abstract, decompose, and structure complex logic (Wing, 2006). However, introductory programming frequently presents high cognitive hurdles for novices (Kazimoglu et al., 2012). While educational robotics has been widely shown to boost engagement and provide immediate feedback in STEM learning, successfully integrating these tools into diverse learning environments and formal curricula remains an ongoing focus of educational research (Ching & Hsu, 2023; Bers et al., 2019).

Learning to code requires managing multiple mental processes simultaneously. According to Cognitive Load Theory (Sweller, 1988; Chandler & Sweller, 1991), human working memory is strictly limited. When instructional tools create a split attention effect, forcing a student to constantly look back and forth between a digital screen interface and a physical robot executing on the floor, extraneous cognitive load spikes. This extraneous friction consumes working memory that should otherwise be devoted to understanding fundamental algorithmic logic.

Seymour Papert’s theory of Constructionism (Papert, 1980) demonstrates that learners construct clearer mental models when actively manipulating physical "objects to think with." Screenless physical robotics provides a direct embodiment of Papert's vision by converting abstract execution steps into tangible, spatial interactions on the floor.

This study builds directly upon research within Maynooth University’s PACT (Programming and Advanced Computational Thinking) initiative and tasks derived from the Bebras Computational Thinking Challenge (Maynooth University, 2025). Specifically, it extends the FYP research of Martin (2024), who demonstrated the feasibility and classroom usability of running PACT robotics challenges in primary schools. This project moves beyond Martin’s general feasibility study by conducting a direct empirical comparison between screenless physical tools and screen based block coding environments.

2.2 Technical Material
This section covers hardware specifications, platform mechanics, task design models, and data collection tools.

Hardware Platforms
Sphero Indi: An entry level educational robot designed for screen-free CT instruction (Sphero, 2021). It uses an underbody optical color sensor to detect physical rubber tiles placed on the floor. Each color corresponds to a pre programmed command (e.g., Green = Accelerate, Yellow = Slow Down, Red = Stop, Blue/Pink = Turns). Users construct physical algorithm paths by arranging tiles, allowing instant spatial debugging without interacting with a digital display.

Sphero BOLT: A programmable robotic sphere controlled via the Sphero Edu application on tablets or computers. Programming is conducted using a visual drag and drop block-coding interface (similar to Scratch). Users assemble sequence blocks on screen, set parameters, and transmit the instructions wirelessly via Bluetooth to execute on the floor.

PACT Task Adaptation & CT Categories
Following the framework established in PACT resource design (Martin, 2024; Maynooth University, 2025), physical task scenarios are structured around four core computational thinking dimensions:

Abstraction: Removing redundant tiles or paths to focus purely on the essential route.

Algorithms: Building step by step tile sequences to navigate a robot from a start location to a destination.

Decomposition: Breaking multi-stage challenges (such as collecting a tool before reaching a goal tile) into distinct sub-problems.

Pattern Recognition: Identifying repeating path loops or tile sequences to optimize navigation efficiency.

Data Collection & Workload Measurement Instruments
To empirically evaluate both modalities, three core instruments are used:

Task Performance Metrics: Stopwatch timers and trial logs record task completion time (seconds) and debugging error frequency.


Cognitive Workload Index (NASA-TLX): An adapted NASA Task Load Index (NASA-TLX) questionnaire (Hart & Staveland, 1988) assesses self reported Subjective Mental Demand, Effort, and Frustration on a standardized scale.

Observational & Survey Logs: Pre/post task qualitative logs record user interaction styles and subjective preferences.

References
Bers, M. U., González-González, C., & Armas-Torres, M. B. (2019). Coding as a playground: Promoting early childhood computational thinking on screen and off. Computers & Education, 138, 89-104.

Chandler, P., & Sweller, J. (1991). Cognitive load theory and the format of instruction. Cognition and Instruction, 8(4), 293-332.

Ching, Y. H., & Hsu, Y. C. (2023). Robotics in computational thinking education for young learners: A review of empirical research. Computers & Education, 194, 104688.

Hart, S. G., & Staveland, L. E. (1988). Development of NASA-TLX (Task Load Index): Results of empirical and theoretical research. Advances in Psychology, 52, 139-183.

Kazimoglu, C., Kiernan, M., Bacon, L., & MacKinnon, L. (2012). Learning programming at the introductory level: An indicator-based approach to assessing computational thinking with video games. Computers & Education, 59(3), 980-999.

Martin, J. (2024). Investigating the Feasibility and Usability of PACT Robotics Lessons in Primary Education. Final Year Project Report, Department of Computer Science, Maynooth University.

Maynooth University. (2025). PACT: Programming and Advanced Computational Thinking Portal. Department of Computer Science.

Papert, S. (1980). Mindstorms: Children, Computers, and Powerful Ideas. Basic Books, Inc.

Sphero. (2021). Sphero Indi Educator Guide Book. Sphero Inc.

Sweller, J. (1988). Cognitive load during problem solving: Effects on learning. Cognitive Science, 12(2), 257-285.

Wing, J. M. (2006). Computational thinking. Communications of the ACM, 49(3), 33-35.
