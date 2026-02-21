# **Strategic Synthesis and Digital Migration of the Evolutionary Computation in Practice (ECiP) Historical Archive: A 15-Year Longitudinal Review (2011–2025)**

The Genetic and Evolutionary Computation Conference (GECCO), as the premier venue for research in the field of natural computation, has long recognized the necessity of bridging the chasm between theoretical innovation and industrial application. Central to this mission is the Evolutionary Computation in Practice (ECiP) track, which has functioned for over fifteen years as a specialized forum for the dissemination of high-level insights into the operationalization of evolutionary algorithms in real-world contexts.1 Unlike the broader academic tracks that prioritize peer-reviewed full papers and theoretical proofs, the ECiP track focuses on the qualitative and managerial complexities of industrial collaboration, bringing together experts who manage corporations, lead large-scale optimization projects, and navigate the intricate landscape of academia-industry partnerships.1

As the digital infrastructure of GECCO evolves, there is an urgent need to consolidate the institutional memory of the ECiP track. This involves not only updating the historical registry of speakers and their contributions but also modernizing the delivery of this data to meet the aesthetic and functional standards of the contemporary scientific community. The transition from legacy content management systems to modern, version-controlled platforms such as GitHub Pages and Quarto Markdown represents a significant opportunity to enhance the accessibility and visual appeal of this historical archive. This report provides a comprehensive longitudinal analysis of the ECiP track from 2011 to 2025, synthesized with a technical roadmap for its digital migration.

## **Digital Transformation of Scientific Archives: From Legacy Systems to Quarto**

The technical evolution of the GECCO web presence is a microcosm of the broader shifts in scientific communication. For over a decade, the conference utilized the Tiki Wiki CMS Groupware system, a platform that served its purpose for early collaborative editing but eventually accumulated significant technical debt.6 Legacy systems like Tiki Wiki often present challenges in terms of mobile responsiveness, search engine optimization (SEO), and the integration of modern design frameworks. The move toward GitHub Pages and Quarto Markdown is not merely a change in hosting but a fundamental shift toward "Documentation as Code," where content is managed with the same rigor and version control as the software it describes.

A scientifically attractive design for an academic archive must prioritize clarity, information density, and the seamless integration of different data types. Quarto, as a multi-language, next-generation version of R Markdown, provides the ideal toolkit for this task. It allows for the production of high-quality static websites that integrate LaTeX for mathematical rigor, responsive Markdown tables for structured data, and customizable CSS/SASS for branding that aligns with the SIGEVO identity.

### **Technical Advantages of the Quarto-GitHub Pages Framework**

The architectural shift to Quarto facilitates a "living archive" approach. By utilizing YAML-based metadata for speaker profiles and talk descriptions, the archive becomes easily searchable and extensible. The use of CSS variables allows for a design that is both professional and visually engaging, incorporating the color palettes and typography expected by the academic community. Furthermore, the integration with GitHub Actions enables automated deployment pipelines, ensuring that the ECiP registry is updated in real-time as new information becomes available.

| Feature | Legacy Tiki Wiki System | Modern Quarto \+ GitHub Pages |
| :---- | :---- | :---- |
| Version Control | Limited to page-level history | Comprehensive Git-based versioning |
| Math Rendering | Variable plugin support | Native, high-quality LaTeX support |
| Responsiveness | Often poor on mobile devices | Built-in Bootstrap 5 responsiveness |
| Data Integration | Manual table entry | Automated listings from YAML/CSV data |
| Aesthetic Control | Constrained by CMS themes | Full SASS/CSS customization |
| Sustainability | Requires server maintenance | Serverless, static hosting on GitHub |

In the context of the ECiP track, this digital modernization allows for a more nuanced presentation of the "insider information" that the track is known for. Instead of fragmented summaries, the Quarto framework can support integrated narratives that connect historical speakers with the specific industrial challenges they addressed, creating a rich educational resource for researchers looking to establish their own industrial partnerships.1

## **The ECiP Track: Organizational Continuity and Mission**

The stability of the ECiP track over the previous fifteen years is largely a product of consistent leadership and a clearly defined mission. Since at least 2008, Thomas Bartz-Beielstein has served as a central figure in the track’s organization.8 His background, spanning both a professorship in Applied Mathematics at TH Köln and a shareholder role in a private optimization firm, exemplifies the dual identity required to lead such a track.8 The involvement of the IDE+A (Intelligent Decision Support and Applied Research) group at TH Köln has provided a robust institutional anchor for the track's activities, including the management of the Industrial Challenge, which has run annually since 2011\.1

The primary mission of ECiP is to provide a venue where well-known speakers with outstanding reputations present background information on establishing reliable cooperation with industrial partners.1 The track targets researchers in academia who are interested in managing industrial projects, offering them valuable hints that extend beyond textbook methodologies.1 This focus on real-world optimization and project management principles distinguishes ECiP from the Real World Applications (RWA) track, which is more focused on the presentation of peer-reviewed results than on the process of cooperation.1

### **Leadership Chronology and Institutional Context**

The organizational structure of the ECiP track has evolved to reflect the global nature of the GECCO community. While Thomas Bartz-Beielstein has remained a constant, he has been joined by various co-organizers who bring diverse regional and technical expertise.

| Era | Key Organizers | Affiliations and Focus |
| :---- | :---- | :---- |
| 2023-2025 | Thomas Bartz-Beielstein, Richard Schulz, Danial Yazdani | IDE+A, TH Köln; University of Technology Sydney 1 |
| 2021-2022 | Thomas Bartz-Beielstein, Bogdan Filipic, Sowmya Chandrasekaran | TH Köln; Jozef Stefan Institute, Slovenia 2 |
| 2011-2020 | Thomas Bartz-Beielstein, Joern Mehnen, David Davis | TH Köln; Cranfield University; VGO Associates 8 |

This institutional continuity has allowed the track to maintain a high standard for invited speakers. The organizers’ professional networks have been instrumental in bringing "high calibre speakers from several industry areas to GECCO," creating what has been described as a "magical place where academia and industry can meet".14

## **Comprehensive Speaker Registry and Talk Synthesis (2011–2025)**

The following analysis updates and completes the list of speakers for the ECiP track, drawing from historical archives, conference booklets, and professional profiles. This registry highlights the track's ability to attract leaders from diverse sectors, including automotive manufacturing, energy management, logistics, and software engineering.

### **The Recent Era: Addressing Hybridity and Emergent Complexity (2021–2025)**

The period from 2021 to 2025 has been marked by two significant shifts: the transition to hybrid conference models and a renewed focus on the "antagonism" between academic foundations and industrial applications.1 The 2025 program, in particular, highlights a critical reflection on why advanced methods proposed in research often fail to achieve practical relevance while simpler strategies succeed.5

| Year | Speaker | Talk Title | Affiliation |
| :---- | :---- | :---- | :---- |
| 2025 | Dr. Roman Kalkreuth | On the antagonism between foundations and applications in graph-based genetic programming | RWTH Aachen, Germany 5 |
| 2025 | Dr. Farha Anjum Khan | Robust Contextual Preferential Bayesian Optimization for Real-World Applications with Biased Data | Continental-Corporation 5 |
| 2025 | Dr. Xavier Bonet-Monroig |  | \[Affiliation Pending\]5 |
| 2022 | Meinolf Sellmann | Modern Hybrids: Machine Learning for Search and Optimization | InsideOpt (CTO) 16 |
| 2021 | Joshua Tenenbaum | Reverse-engineering core common sense with the tools of probabilistic programs | MIT, USA 17 |
| 2021 | Marc Mézard | Statistical Physics and Statistical Inference | École Normale Supérieure, France 17 |

Roman Kalkreuth’s 2025 contribution is particularly noteworthy for its pedagogical value. He addresses the gap where "relatively simple 1+lambda search strategies" originally proposed as base algorithms for Cartesian Genetic Programming (CGP) have been more successful in real-world applications than the more complex genetic variation methods proposed in recent years.5 This aligns with the ECiP mission to look beyond textbooks and understand the specific properties that make an algorithm "practice-ready."

### **The Middle Period: Globalization and Surrogate Models (2016–2020)**

During this period, the ECiP track matured alongside the rise of surrogate-assisted evolutionary optimization (SAEOpt). As real-world simulations became increasingly expensive, the need for data-driven models to guide the search process became a primary industrial requirement.16 This period also saw GECCO’s expansion into Asia (Kyoto 2018\) and the consolidation of the "Industrial Challenge" as a key engagement tool.

| Year | Speaker | Contribution Context | Affiliation |
| :---- | :---- | :---- | :---- |
| 2019 | Markus Wagner | Invited Speaker (Optimising Wave Energy Converters) | University of Adelaide 22 |
| 2018 | Thomas Bartz-Beielstein | Event Chair and Tutorial (EC in Practice) | TH Köln 8 |
| 2017 | Kate Smith-Miles | Keynote/Invited (Visualising diversity of benchmark instances) | University of Melbourne 23 |
| 2016 | Iñaki Hidalgo | Workshop/Track Leadership (Practice focus) | Universidad Complutense de Madrid 20 |

The work of Markus Wagner in 2019 exemplifies the interdisciplinary nature of the track. His focus on "Optimising the Wave Energy Converters" involved not just metaheuristic methods but also the use of adaptive neuro-surrogate-based optimization to handle the high costs associated with placing power take-off units.22 This project received a Best Paper Award in the RWA track, highlighting how the principles discussed in the ECiP track translate into award-winning academic output.22

### **The Foundational Era: Establishing the Industrial Interface (2011–2015)**

The early years of the ECiP track were critical for defining the scope of industrial EC. Thomas Bartz-Beielstein, Joern Mehnen, and David Davis worked to ensure that GECCO was not just a theoretical gathering but a "magical place where academia and industry can meet".14 This era established the "Industrial Challenge," which allowed participants to tackle real-world problems provided by companies such as ArcelorMittal.20

| Year | Organizers/Key Contributors | Primary Industrial Focus | Affiliations |
| :---- | :---- | :---- | :---- |
| 2014 | Thomas Bartz-Beielstein, Joern Mehnen | Logistics and Manufacturing | TH Köln; Cranfield University 8 |
| 2012 | Thomas Bartz-Beielstein, David Davis | Statistics for EC: A Visual Approach | TH Köln; VGO Associates 8 |
| 2011 | Thomas Bartz-Beielstein, Joern Mehnen, David Davis | Establishing industry-academia cooperation | TH Köln; Cranfield; VGO 14 |

In 2011, the organizers were praised for bringing speakers from diverse industry areas, a tradition that has continued for over a decade.14 The focus during this time was often on the "Practice of Evolution," teaching attendees how to manage the lifecycle of an optimization project, from the initial client meeting to final deployment.

## **The GECCO Industrial Challenge: A Longitudinal Review**

A vital component of the ECiP track is the Industrial Challenge, an annual competition that provides a bridge between real-world data and academic algorithms. Since its inception in 2011, the challenge has invited researchers to solve optimization problems defined by actual industrial partners, often using anonymized data from manufacturing, logistics, or energy sectors.8

The 2024 and 2025 editions of the challenge continue this tradition, focusing on complex problems such as the optimal placement of PV systems in energy domains and dynamic stacking optimization in uncertain environments.11 These competitions are organized by the same core team that leads the ECiP track, ensuring that the lessons learned from the track are directly applied in a competitive setting.11

| Competition Year | Focus / Topic | Lead Organizers |
| :---- | :---- | :---- |
| 2024 | Evolutionary Computation in the Energy Domain (PV Systems) | Joao Soares, Fernando Lezama, Zita Vale 25 |
| 2020 | Industrial Challenge (Dynamic Stacking Optimization) | Frederik Rehbach, Thomas Bartz-Beielstein 11 |
| 2019 | Online Event Detection for Water Quality Control | Frederik Rehbach, Steffen Moritz, T. Bartz-Beielstein 10 |
| 2011-Present | GECCO Industrial Challenge Series | Thomas Bartz-Beielstein (Founder/Organizer) 8 |

The Industrial Challenge has a significant impact on the field, as it provides a rare opportunity for researchers to test their algorithms on "dirty" data—datasets that include noise, missing values, and non-standard constraints that are rarely found in textbook benchmarks.1 The success of this series underscores the track's commitment to extending EC practice beyond theoretical ideals.

## **Synthesis of Thematic Trends in Industrial Evolutionary Computation**

An analysis of fifteen years of ECiP talk titles and abstracts reveals several second- and third-order insights into the evolution of the field. These trends indicate how the focus of industrial EC has shifted in response to broader technological advancements, particularly in machine learning and data science.

### **From Black-Box to Gray-Box Optimization**

In the early 2010s, the focus was often on treating industrial problems as "black boxes," where the algorithm had no knowledge of the underlying system.15 However, by the early 2020s, there was a clear shift toward "gray-box" optimization, where domain knowledge and surrogate models are used to enhance the search process.16 Meinolf Sellmann’s 2022 talk on "Modern Hybrids" is a primary example of this, summarizing 15 years of work on the use of Machine Learning for Search and Optimization.16

### **The Rise of Surrogate-Assisted Optimization**

As real-world optimization problems often involve computationally expensive simulations—such as Computational Fluid Dynamics (CFD) or complex structural analysis—the field has increasingly turned to surrogate models.16 The 2017 SAEOpt workshop and subsequent contributions highlight the development of acquisition functions designed to minimize the number of objective function evaluations required to find an optimal solution.20 This trend is a direct causal response to the industrial need for "fast enough" solutions that balance accuracy with computational cost.

### **The Emerging Synergy with Large Language Models (LLMs)**

The most recent data points to a burgeoning interest in the intersection of EC and Large Language Models. The 2024 workshop on "Large Language Models for and with Evolutionary Computation" (LLMfwEC) and tutorials on genetic improvement using search methods indicate that the community is exploring how LLMs can facilitate the generation of code, the discovery of new algorithm variants, and the exploration of prompt spaces.21 This represents a new frontier for "Practice," where the "coder" is no longer purely human, and the search process is augmented by generative AI.

## **Technical Implementation: Creating a Scientifically Attractive Archive**

As an experienced web designer tasked with managing this archive via GitHub Pages and Quarto, the implementation must follow rigorous structural and aesthetic principles. A scientifically attractive design is characterized by its ability to present complex information without overwhelming the user. In the case of the ECiP track, this involves the careful use of data visualization and structured content.

### **Quarto Project Structure and YAML Metadata**

To ensure the archive is maintainable, a Quarto project should utilize a data-driven approach. Instead of hard-coding speaker lists into HTML, the data should be stored in YAML or CSV files. This allows for the use of Quarto's listings feature to automatically generate speaker galleries, talk summaries, and chronological registries.

YAML

\# Example \_quarto.yml for ECiP Archive  
project:  
  type: website

website:  
  title: "GECCO ECiP Historical Archive"  
  navbar:  
    left:  
      \- text: "Home"  
        href: index.qmd  
      \- text: "Speakers"  
        href: speakers.qmd  
      \- text: "Industrial Challenge"  
        href: industrial-challenge.qmd  
      \- text: "Chronology"  
        href: chronology.qmd

format:  
  html:  
    theme:  
      light: \[cosmo, custom.scss\]  
      dark: \[darkly, custom.scss\]  
    toc: true  
    number-sections: true  
    code-fold: true

The use of a custom SCSS file (custom.scss) is essential for "scientifically attractive" design. This allows for the definition of typography that prioritizes readability (e.g., sans-serif headers with serif body text) and a color palette that reflects the professionalism of the ACM SIGEVO community.

### **LaTeX for Algorithmic Rigor**

In a professional scientific report, algorithmic descriptions must be presented with mathematical precision. Quarto’s native support for MathJax and LaTeX allows for the seamless inclusion of the formulas that define the strategies discussed by ECiP speakers. For instance, a discussion of the ![][image1] strategy mentioned in Roman Kalkreuth’s talk can be formally defined as:

![][image2]  
where ![][image3] are the offspring generated via mutation of the current best solution ![][image4].5 This level of detail ensures that the archive serves not just as a historical record but as a technical resource for future researchers.

## **Strategic Outlook: The Future of Evolutionary Computation in Industry**

The longitudinal review of the ECiP track suggests that the next decade of industrial EC will be defined by the need for robustness, interpretability, and ethical scaling. As evolutionary systems are increasingly deployed in critical infrastructure, the lessons shared by ECiP speakers will become even more relevant.

### **The Shift Toward Interpretable Control**

The 2024 "Interpretable Control Competition" and the emphasis on explainable AI (XAI) indicate that industrial clients are no longer satisfied with "black-box" decisions.12 Future ECiP speakers will likely focus on how to evolve controllers and models that are not only performant but also "human-readable," allowing engineers to understand why a specific optimization decision was made.12

### **Sustainability and Computational Efficiency**

With the growing focus on the environmental impact of AI, the ECiP track is well-positioned to lead the discussion on sustainable optimization.13 The appointment of SIGEVO’s first-ever Sustainability Officer and the inclusion of sustainability grants at GECCO 2024 suggest that the future of practice will involve a focus on algorithms that minimize carbon footprints while maximizing industrial efficiency.13

### **Final Conclusion: The Enduring Value of the ECiP Interface**

The Evolutionary Computation in Practice track has demonstrated remarkable resilience and relevance over the previous fifteen years. By providing a dedicated space for the discussion of project management, industrial scaling, and the "messy" realities of real-world data, the track has ensured that evolutionary computation remains a vital tool for industrial innovation.1

The update and completion of the speaker registry, when integrated into a modern digital framework like Quarto and GitHub Pages, will provide the GECCO community with a powerful asset. It will serve as both a testament to the track’s historical achievements and a roadmap for future researchers who seek to bridge the gap between foundations and applications. As we look toward GECCO 2025 and beyond, the ECiP track will undoubtedly continue to be the "magical place" where theory meets practice, guided by the experts who run the companies and projects that shape our world.1

The meticulous curation of this 15-year history—spanning from the early contributions of David Davis and Joern Mehnen to the modern insights of Meinolf Sellmann and Roman Kalkreuth—highlights a consistent trajectory of growth, globalization, and technological sophistication.5 By documenting these contributions in a scientifically attractive, data-driven archive, the community honors the "insider information" that has made evolutionary computation a pillar of modern industrial optimization.

#### **Referenzen**

1. EC in Practice \- GECCO 2024, Zugriff am Februar 21, 2026, [https://gecco-2024.sigevo.org/EC-in-Practice.html](https://gecco-2024.sigevo.org/EC-in-Practice.html)  
2. Evolutionary Computation in Practice (ECiP) \- gecco 2021, Zugriff am Februar 21, 2026, [https://gecco-2021.sigevo.org/EC-in-Practice.html](https://gecco-2021.sigevo.org/EC-in-Practice.html)  
3. EC in Practice \- GECCO 2022, Zugriff am Februar 21, 2026, [https://gecco-2022.sigevo.org/EC-in-Practice.html](https://gecco-2022.sigevo.org/EC-in-Practice.html)  
4. EC in Practice \- GECCO 2025, Zugriff am Februar 21, 2026, [https://gecco-2025.sigevo.org/EC-in-Practice](https://gecco-2025.sigevo.org/EC-in-Practice)  
5. Evolutionary Computation in Practice at ACM GECCO \- spotseven.de, Zugriff am Februar 21, 2026, [https://www.spotseven.de/?page\_id=508](https://www.spotseven.de/?page_id=508)  
6. Call for Papers \- gecco 2024 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2024.sigevo.org/Call-for-Papers.html](https://gecco-2024.sigevo.org/Call-for-Papers.html)  
7. Competition Proposals \- gecco 2025 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2025.sigevo.org/Competition-Proposals](https://gecco-2025.sigevo.org/Competition-Proposals)  
8. Program Tracks \- GECCO 2018, Zugriff am Februar 21, 2026, [http://gecco-2018.sigevo.org/index.html/Program+Tracks](http://gecco-2018.sigevo.org/index.html/Program+Tracks)  
9. Competitions \- gecco 2018 \- sigevo, Zugriff am Februar 21, 2026, [http://gecco-2018.sigevo.org/index.html/tiki-index3aa7.html?page=Competitions](http://gecco-2018.sigevo.org/index.html/tiki-index3aa7.html?page=Competitions)  
10. Competitions \- gecco 2019 \- sigevo, Zugriff am Februar 21, 2026, [http://gecco-2019.sigevo.org/index.html/Competitions](http://gecco-2019.sigevo.org/index.html/Competitions)  
11. Competitions \- gecco 2020 \- sigevo, Zugriff am Februar 21, 2026, [http://gecco-2020.sigevo.org/index.html/Competitions](http://gecco-2020.sigevo.org/index.html/Competitions)  
12. Tracks \- gecco 2025 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2025.sigevo.org/Tracks](https://gecco-2025.sigevo.org/Tracks)  
13. Genetic and Evolutionary Computation Conference 2024, Zugriff am Februar 21, 2026, [http://www0.cs.ucl.ac.uk/staff/W.Langdon/gecco2024/GECCO\_2024\_Booklet\_Professional\_10July.pdf](http://www0.cs.ucl.ac.uk/staff/W.Langdon/gecco2024/GECCO_2024_Booklet_Professional_10July.pdf)  
14. Sharp bounds by probability-generating functions and variable drift \- SciSpace, Zugriff am Februar 21, 2026, [https://scispace.com/pdf/sharp-bounds-by-probability-generating-functions-and-jbqaj8qzk9.pdf](https://scispace.com/pdf/sharp-bounds-by-probability-generating-functions-and-jbqaj8qzk9.pdf)  
15. Professional Report \- International Society for Genetic and Evolutionary Computation ISGEC, Zugriff am Februar 21, 2026, [http://www.isgec.org/gecco-2009/docs/gecco09-conference-program-final-plus2.pdf](http://www.isgec.org/gecco-2009/docs/gecco09-conference-program-final-plus2.pdf)  
16. Keynotes \- GECCO 2022, Zugriff am Februar 21, 2026, [https://gecco-2022.sigevo.org/Keynotes.html](https://gecco-2022.sigevo.org/Keynotes.html)  
17. Keynotes \- GECCO 2021, Zugriff am Februar 21, 2026, [https://gecco-2021.sigevo.org/Keynotes.html](https://gecco-2021.sigevo.org/Keynotes.html)  
18. Organizers \- gecco 2022 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2022.sigevo.org/Organizers.html](https://gecco-2022.sigevo.org/Organizers.html)  
19. Tutorials \- gecco 2018 \- sigevo, Zugriff am Februar 21, 2026, [http://gecco-2018.sigevo.org/index.html/tiki-indexc467.html?page=Tutorials](http://gecco-2018.sigevo.org/index.html/tiki-indexc467.html?page=Tutorials)  
20. Workshops \- gecco 2017 \- sigevo, Zugriff am Februar 21, 2026, [http://gecco-2017.sigevo.org/index.html/Workshops.html](http://gecco-2017.sigevo.org/index.html/Workshops.html)  
21. Workshops \- gecco 2024 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2024.sigevo.org/Workshops.html](https://gecco-2024.sigevo.org/Workshops.html)  
22. APrf Markus Wagner \- Researcher Profiles \- The University of Adelaide, Zugriff am Februar 21, 2026, [https://researchers.adelaide.edu.au/profile/markus.wagner](https://researchers.adelaide.edu.au/profile/markus.wagner)  
23. in this issue \- SIGEVOlution, Zugriff am Februar 21, 2026, [https://evolution.sigevo.org/issues/SIGEVOlution0704.pdf](https://evolution.sigevo.org/issues/SIGEVOlution0704.pdf)  
24. Organizers \- gecco 2025 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2025.sigevo.org/Organizers](https://gecco-2025.sigevo.org/Organizers)  
25. Call for Competition Entries \- gecco 2024, Zugriff am Februar 21, 2026, [https://gecco-2024.sigevo.org/Call-for-Competition-Entries.html](https://gecco-2024.sigevo.org/Call-for-Competition-Entries.html)  
26. Competitions \- gecco 2024 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2024.sigevo.org/Competitions.html](https://gecco-2024.sigevo.org/Competitions.html)  
27. Tutorials \- gecco 2019 \- sigevo, Zugriff am Februar 21, 2026, [http://gecco-2019.sigevo.org/index.html/Tutorials](http://gecco-2019.sigevo.org/index.html/Tutorials)  
28. Accepted Workshop Papers \- gecco 2024 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2024.sigevo.org/Accepted-Workshop-Papers.html](https://gecco-2024.sigevo.org/Accepted-Workshop-Papers.html)  
29. Tutorials \- gecco 2024 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2024.sigevo.org/Tutorials.html](https://gecco-2024.sigevo.org/Tutorials.html)  
30. Main Achievements \- School of Computer and Mathematical Sciences \- The University of Adelaide, Zugriff am Februar 21, 2026, [https://cs.adelaide.edu.au/users/markus/pub/MarkusWagner-CV-220722.pdf](https://cs.adelaide.edu.au/users/markus/pub/MarkusWagner-CV-220722.pdf)  
31. Organizers \- gecco 2024 \- sigevo, Zugriff am Februar 21, 2026, [https://gecco-2024.sigevo.org/Organizers.html](https://gecco-2024.sigevo.org/Organizers.html)

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAC0AAAAYCAYAAABurXSEAAABLklEQVR4Xu2VMUoDQRiF/1Rikc7GQhB7OzshFxA8gJADxBCNoEeIWMQTpA2kCIQcIPfIAUwjgVSpQkD/x8y6+Jw1OzNrQJgPHsu+/8E82H93RRKJf8Wx6pDNXTyqWmzukRPVh9WvjFQbycO338d751xMjyYPiogt3WMjEPTYsllEbOkXNgKZSYkVyYgt3WcjkLqYLs88cBFb+pWNCEq9kAChNpseVFl6IKbPAQ8YhDpsFnDh0NDhZfKhoVqL6TOh2Q8QumOzgGuHpg4vU1muJF+LUiuCQJdND2LX40ZMh5q9x1PH/WkWcIHAA5sexJTGBwDnH5EPb07eFwgjEPPZCi2Np4uzL3mgrMSxImPVUrVQvdnru5hfuy+hpVHqiU3LmZj5PQ+qIrR0IpFI/DGfY+tFdndnp0IAAAAASUVORK5CYII=>

[image2]: <data:image/png;base64,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>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGUAAAAYCAYAAADjwDPQAAADNklEQVR4Xu2ZS8hNURiGP5eI3ClFykDKNUwk5TaSAWGAzFxKEn5JDCgTEyTCAPmHFHKNMDVwyWWCiAwkyi1JSm7f217b/s571trnP5d9fmf/+6m3s793nb3WOd/ae+211hapjTdseHjLRhdggmoimx76q1axWQ832FCmqu6yqTxiI8f0UJ0hr5vqp2o1+WCdaiybtcKdskt1RPydclXVh82c8oQNx2zVHzYdv9mohYuqoWwqu8XfKYNUl9nMKaHEA5ThrmEeSHSH1UWo4VCngNA5eaKfqp1Nw0PVcTaVlartbFZLKMHolHtsOkLn5ImFqjY2DePEn4fJqnNsVouvYoBOuc+mI3ROntinWsqmY5jqtkR5GEJlGN5xF9VFKMHoFIyPPkLn5IkNqk1sKqNUH93xadUtUwYmqQ6TV8Ix1Vo2lenmOJRgdEpo+hs6p1XAEHNKNZj8nhJd6WCmRPmzjJHS2RUe6JyLZarF5P3jhyQnzTX+GufFXFMNMDH4pvqk+qD6ItGPjcED8KaJW415qv3in9YifmniX+YY8PfBZ9V8E2NY8y4ZTkoyLUNFC0wZEm0rx0r0vIkrgcVU3VO+TiT+7+3mOAbxehMjV9USXKfsdJ97xd8wd8ILitMIzchahTnuE3l4ZvxpzrNrj76qEyauxHKJhrhU0Mg7E8fDGbZQmI7sa9m6WhkkG3nAvlbMFecxs1Sj2fTQS7WVTR9oZImJtzmvq3NQyvOAGM+HTBku5Q3joc1eI0Gn20kBM0JSZiYO7LulMUVKZ48+KtXxVMrzgHgLeZmAhjD9A9h+RnwhKW4oGyWq/ysXGFDOybDEz8C0xVelOvC8RDk2TkNgHWHruOPi7sbLjHj6Cx1yn+NLvtFYXkm0rR0Ce0JpFwXustcSLdBCYOjh9YMFK+z3kt5x4LEkucFFUOn7DQFDheW6NKfhZrTRETBUh8BMy4LfzO9NGg5WqmjoqIsxzUNsFzlZ0Fv8O6fNBi+asFvrA1N6e+EcoDgzRqq+u+OBEjW6IinODF4BdxbBBZzyXLXDHePtIXLTtMXwDNVZ1R4uyBBswfwP+F4+WTarLqkWcUFBQUFBQQl/AXQirUzEVcrcAAAAAElFTkSuQmCC>

[image4]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABsAAAAYCAYAAAALQIb7AAABMklEQVR4Xu2UsUtCURTGT7QUNbS5RCBtLkJT/QGuNto/4ChuCRHODi6NzREEjYFLW5uIkYK7g2DQ1iK02Hfeu493/LovfE/H94MPzvndyz3vPeWKZGfCwjBnsQkzFuCA+g/qM3GM3LAES+p7yD651HyxAJfIiNwR8kIuNfwG2tvw2kb4DvA5Jcmvje8An1OS/NrwAVVkTC6C965wh9RN30FuTa/wAW9IzdUtuyB/9wYUJH66BvIj8cYh0nW18m1q5QSZIo/kD5FXcgH2CXST9mXk3NVXZv0CaZo+iWdkl6VyZuprWR2+Z+qIBQsPAxY+9DN5vzXRZ2H4ZJGEDnpguS30WtEBpxL/XiWz/t/tnpp7CQfopfnu6qJb0z/Jk6u3wo6EAzQVCd8w6ttmX05OTjZ+AbUSP5QzbrN8AAAAAElFTkSuQmCC>