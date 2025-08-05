<html>
<head>
  <meta charset="UTF-8">
  <title>Public-Sector AI Curriculum</title>
  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: #fff;
    }

    .page-wrapper {
      max-width: none;
      width: 100%;
    }

    .layout-wrapper {
      display: flex;
      align-items: flex-start;
      padding: 2rem 2rem 2rem 1rem;
      max-width: none;
      margin: 0;
      gap: 2rem;
      width: 100%;
    }

    #sticky-nav {
      position: sticky;
      top: 1rem;
      align-self: flex-start;
      width: 180px;
      background-color: #f3f3f3;
      border: 1px solid #ddd;
      padding: 1em;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
      font-size: 0.9em;
      flex-shrink: 0;
    }

    #sticky-nav ul {
      list-style: none;
      padding-left: 0;
      margin: 0;
    }

    #sticky-nav li {
      margin-bottom: 0.5em;
    }

    .main-content {
      flex: 1;
      min-width: 0;
      max-width: none;
      padding-right: 1rem;
    }

    .footer-wrapper {
      width: 100vw;
      position: relative;
      left: 50%;
      right: 50%;
      margin-left: -50vw;
      margin-right: -50vw;
      background-color: #ffeeee;
      border-top: 1px solid #ddd;
      margin-top: 3rem;
      padding: 2rem 0;
      font-size: 0.9em;
      color: #666;
      text-align: center;
      box-sizing: border-box;
    }

    .footer-content {
      padding: 0 2rem;
      max-width: none;
      margin: 0;
    }

    /* Mobile styles */
    @media (max-width: 768px) {
      .layout-wrapper {
        flex-direction: column;
        padding: 1rem;
        margin: 0;
        gap: 1rem;
      }

      #sticky-nav {
        width: 100%;
        position: relative;
        box-shadow: none;
        margin-bottom: 1rem;
      }

      .main-content {
        padding-right: 0;
      }

      .footer-wrapper {
        width: 100vw;
        position: relative;
        left: 50%;
        right: 50%;
        margin-left: -50vw;
        margin-right: -50vw;
        padding: 1.5rem 0;
      }

      .footer-content {
        padding: 0 1rem;
        max-width: none;
      }
    }
  </style>
</head>
<body>
  <div class="page-wrapper">
    <div class="layout-wrapper">
      <div id="sticky-nav">
        <strong>Jump to:</strong>
        <ul>
          <li><a href="#introduction-to-ai">Introduction to AI</a></li>
          <li><a href="#fundamentals-of-operationalizing-ai-mastering-ai-system-lifecycle-from-theory-to-practice">Operationalizing AI</a></li>
          <li><a href="#responsible-ai-principles-policies-practices">Responsible AI</a></li>
          <li><a href="#generative-ai-applications-implications-and-governance">Generative AI</a></li>
          <li><a href="#developing-your-own-curriculum">Developing Your Own Curriculum</a></li>
        </ul>
      </div>

      <div class="main-content">
        <img src="ofai-cmu.png" width="500"> <br><br>

        <h1>Public-Sector AI Curriculum</h1>

        <p>In order to prepare professionals to work with open-source AI in the public sector, Carnegie Mellon University's Heinz College of Information Systems and Public Policy has released an open-source curriculum of four courses:</p>

        <ul>
          <li>Introduction to AI</li>
          <li>Fundamentals of Operationalizing AI: Mastering AI System Lifecycle from Theory to Practice</li>
          <li>Responsible AI: Principles, Policies, and Practices</li>
          <li>Generative AI: Applications, Implications, and Governance</li>
        </ul>

        <p>Collectively, these courses introduce students to the knowledge and skills requisite to understand the foundations of AI design and implementation, including opportunities, risks, limitations, and frontier developments.</p>

        <h2 id="introduction-to-ai">Introduction to AI</h2>
        <h3>Skills</h3>
        <ul>
          <li><strong>Communication and Interpersonal Skills:</strong> Written and verbal communication, teamwork and collaboration, conflict resolution</li>
          <li><strong>Analysis and Critical Thinking Skills:</strong> Broad socio-technical perspective, ethical analysis, policy analysis</li>
          <li><strong>Applied and Functional Skills:</strong> Project management, problem scoping, applying AI to specific problems, understanding uses and limitations of AI</li>
          <li><strong>Technical Skills:</strong> Data collection, analysis, processing; programming; foundational AI concepts (ML, LLMs, neural networks, etc.)</li>
        </ul>
        <h3>Syllabus</h3>
      <iframe src="Introduction to AI.pdf" width="100%" height="600px"></iframe> <br><br>

        <h2 id="fundamentals-of-operationalizing-ai-mastering-ai-system-lifecycle-from-theory-to-practice">Fundamentals of Operationalizing AI</h2>
        <h3>Skills</h3>
        <ul>
          <li><strong>Communication, Critical Thinking, and Interpersonal Skills:</strong> written and verbal communication, teamwork and collaboration, systems thinking</li>
          <li><strong>Strategy and Innovation Skills:</strong> project management, business strategy, cost-benefit and ROI analysis</li>
          <li><strong>Ethics and Governance Skills:</strong> risk evaluation and mitigation, governance frameworks, ethical and policy analysis</li>
          <li><strong>Technical and AI Interaction Skills:</strong> end-to-end AI lifecycle management, MLOps, Jupyter Lab, Docker, Kubernetes, Kubeflow, Kafka, Evidently, basic data science</li>
        </ul>
        <h3>Syllabus</h3>
      <iframe src="Operationalizing AI.pdf" width="100%" height="600px"></iframe> <br><br>

        <h2 id="responsible-ai-principles-policies-practices">Responsible AI</h2>
        <h3>Skills</h3>
        <ul>
          <li><strong>Communication and Interpersonal Skills:</strong> teamwork and collaboration, written and verbal communication</li>
          <li><strong>Ethics and Governance Skills:</strong> NIST AI Risk Management Framework, governance strategy, regulatory fluency, ethical analysis, policy analysis, impact assessments and audits</li>
          <li><strong>Technical and AI Interaction Skills:</strong> foundational concepts of AI; understanding explainability, transparency, interpretability, bias, and fairness of models; privacy and security</li>
        </ul>
        <h3>Syllabus</h3>
      <iframe src="Responsible AI.pdf" width="100%" height="600px"></iframe> <br><br>

        <h2 id="generative-ai-applications-implications-and-governance">Generative AI</h2>
        <h3>Skills</h3>
        <ul>
          <li><strong>Communication, Strategy, and Critical Thinking Skills:</strong> strategic literacy, policy analysis, policy writing, regulatory fluency</li>
          <li><strong>Technical and AI Interaction Skills:</strong> AI fluency, foundational concepts of generative AI, adaptability to new technologies, applications of AI</li>
        </ul>
        <h3>Syllabus</h3>
      <iframe src="GenAI.pdf" width="100%" height="600px"></iframe> <br><br>

        <h2 id="developing-your-own-curriculum">Developing Your Own Curriculum</h2>
        <div style="border: 1px solid #ddd; background-color: #f3f3f3; padding: 1em 1.5em; margin-top: 1em; margin-bottom: 2em; border-radius: 8px;">
          <p>The above syllabi outline content and readings relevant to the learning objectives covered by each course. In order to build upon the syllabi and develop courses relevant to your specific student population, LLM prompts can be useful for developing detailed course materials and related activities.</p>

          <strong>Tips for using LLMs for Curriculum Development:</strong>
          <ul>
            <li>Try entering prompts into different LLMs, such as NotebookLM and several chatbots.</li>
            <li>Use sufficient context to prompt the LLM, including course goals, duration, and student background.</li>
            <li>Describe your audience – their level of experience and learning needs.</li>
            <li>Be specific: e.g. "The class presentation should contain 15 slides..."</li>
            <li>Iterate and refine based on results.</li>
          </ul>

          <strong>Prompts to develop specific content:</strong>
          <ul>
            <li>Create an interactive activity focused on <em>AI interpretability methods</em> for <em>20 graduate students</em> in <em>small groups</em>, 20–30 minutes.</li>
            <li>Develop a <em>60-minute</em> lesson on <em>the EU AI Act</em> for graduate students.</li>
          </ul>

          <strong>Prompts for specific skills:</strong>
          <ul>
            <li>Create an activity on <em>AI policy writing</em> for <em>35 undergraduates</em>, in <em>pairs</em>, for <em>15 minutes</em>.</li>
            <li>Design a lesson on <em>cost-benefit analysis</em> for <em>graduate students</em> with interactive activities, 80 minutes total.</li>
          </ul>

          <p>For more tips on LLM prompt engineering for curriculum development, see <a href="https://ieeexplore.ieee.org/document/10869091">this article</a>.</p>
        </div>
      </div>
    </div>
  </div>

  <div class="footer-wrapper">
    <div class="footer-content">
      <p>
        A project of the <a href="https://www.cmu.edu/engin/programs/ofai.html">Open Forum for AI</a> created by <a href="https://www.heinz.cmu.edu/">Carnegie Mellon University's Heinz College of Information Systems and Public Policy</a> in partnership with the <a href="https://noblereach.org/">NobleReach Foundation</a>.
      </p>
    </div>
  </div>
</body>
</html>
