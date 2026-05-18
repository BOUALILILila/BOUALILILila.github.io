---
layout: cv
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Experience
***
<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-briefcase"></i> Data Scientist </th>
         <th>Oct. 2023 – present</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td><a href="https://mindflow.io/"> Mindflow </a></td>
        <td>Paris, France</td>
      </tr>
      <tr>
         <td colspan="2">
            <ul>
               <li>Designed and deployed a production-grade multi-agent orchestration engine for workflow automation, enabling natural-language interaction with 4000+ API integrations and custom agents. [Patent Pending]</li>
               <li>Mitigated operational risk with a security-first execution layer featuring credential-scoped tool execution, human-in-the-loop (HITL) approval gates for high-stakes API actions, and full execution traceability.</li>
               <li>Engineered a hierarchical orchestration engine with long-term memory and RAG-based tool discovery, enabling the system to handle complex, multi-turn tasks while minimizing context bloat.</li>
               <li>Developed data augmentation pipelines for API documentation and tool metadata, generating provider-specific agent skills and improving tool retrieval quality.</li>
               <li>Designed an evaluation framework to benchmark LLM planning and tool-use capabilities across standard and edge-case scenarios, enabling regression testing and model drift monitoring over time.</li>
            </ul>
            <p><b>STACK:</b> AWS Cloud, Amazon Bedrock, OpenAI, Gemini, Mistral, LiteLLM, RAG, multi-agent orchestration.</p>
         </td>
      </tr>
   </tbody>
</table>

<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-briefcase"></i> Postdoc Research Fellowship </th>
         <th>Dec. 2022 – Sept. 2023</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td><a href="https://www.liglab.fr/en"> LIG, University of Grenoble Alps </a> </td>
        <td>Grenoble, France</td>
      </tr>
      <tr>
         <td colspan="2">
            <ul>
               <li>Investigated systematic compositional generalization in transformer-based seq2seq models by incorporating syntactic structure into the decoding process through hyperbolic representations of dependency trees.</li>
               <li>Designed, trained, and evaluated a hybrid Euclidean–Hyperbolic transformer architecture for structure-aware sequence generation.</li>
            </ul>
            <p><b>STACK:</b> Transformers, Fairseq, PyTorch, Geoopt.</p>
         </td>
      </tr>
   </tbody>
</table>

### Research internships

<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-briefcase"></i> A Study of Term-Topic Embeddings </th>
         <th>June 2021 – Feb. 2022</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td><a href="https://www.mpi-inf.mpg.de/home"> Max Planck Institute for Informatics (MPI) </a> </td>
        <td>Saarbrücken, Germany</td>
      </tr>
      <tr>
         <td colspan="2">
            <b>Advisor</b> Andrew Yates
            <ul>
               <li>Studied advancements with the ColBERT architecture, which relies on token-level representations with late interactions for document ranking.</li>
               <li>Proposed a structured distillation approach for ColBERT contextualized token embeddings using aggregated frozen pre-trained term-topic embeddings representing token-level contextual semantics.</li>
            </ul>
         </td>
      </tr>
   </tbody>
</table>

<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-briefcase"></i> Research on Microblog Retrieval and Summarization </th>
         <th>Dec. 2018 – July 2019</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td><a href="https://www.irit.fr/"> Institut de Recherche en Informatique de Toulouse (IRIT) </a></td>
        <td>Toulouse, France</td>
      </tr>
      <tr>
         <td colspan="2">
            <b>Advisor</b> Mohand Boughanem
            <ul>
               <li>Developed a tweet summarization pipeline leveraging deep learning models for semantic tweet representation and relevance ranking with respect to user interests.</li>
            </ul>
         </td>
      </tr>
   </tbody>
</table>

## Education
***
<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-graduation-cap"></i> Ph.D in Computer Science</th>
         <th>2019-2022</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td>IRIT Laboratory, University of Paul Sabatier Toulouse</td>
        <td>Toulouse, France</td>
      </tr>
      <tr>
         <td colspan="2">- <b>Thesis Topic</b> Studying Relevant Signals for Document Retrieval using Transformer Models</td>
      </tr>
      <tr>
         <td colspan="2">- <b>Highlights</b> Enhancing, fine-tuning, and evaluating encoder models for ad hoc retrieval based on cross-encoder and dual-encoder architectures, using single-vector and multi-vector representations, using direct supervision or distillation from teacher models.</td>
      </tr>
      <tr>
         <td colspan="2">- <b>Area of study</b> Deep Learning, Information Retrieval, and Natural Language Processing</td>
      </tr>
   </tbody>
</table>

<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-graduation-cap"></i> Master's degree in Computer Science and Engineering</th>
         <th>2018-2019</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td>Higher National School of Computer Science (ESI)</td>
        <td>Algiers, Algeria</td>
      </tr>
      <tr>
         <td colspan="2">- <b>Area of study</b> Deep Learning, Information Retrieval, and Natural Language Processing</td>
      </tr>
   </tbody>
</table>

<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-graduation-cap"></i> Engineering degree in Computer Science and Engineering (Valedictorian)</th>
         <th>2014-2019</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td>Higher National School of Computer Science (ESI)</td>
        <td>Algiers, Algeria</td>
      </tr>
      <tr>
         <td colspan="2">Majored in Information Systems & Software</td>
      </tr>
   </tbody>
</table>

## Projects
***
<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-code"></i> <a href="https://github.com/BOUALILILila/DeepResearchPy">DeepResearchPy</a></th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>A Python package for automated deep query investigation, adapted from JinaAI's node-deepsearch, it iteratively searches, reads, and reasons across the web until finding a satisfactory answer or reaching a token budget limit.</td>
      </tr>
   </tbody>
</table>

<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-code"></i> <a href="https://github.com/BOUALILILila/SciWatch">SciWatch</a></th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>A Python package that delivers scheduled newsletters with relevant scientific papers, using boolean retrieval for query matching.</td>
      </tr>
   </tbody>
</table>

<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-code"></i> <a href="https://github.com/BOUALILILila/HybridSeq2Seq">HybridSeq2Seq</a></th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td>Transformer-based Euclidean-hyperbolic hybrid seq2seq model for COGS semantic parsing, leveraging hyperbolic embeddings to capture hierarchical structures and enhance compositional generalization.</td>
      </tr>
   </tbody>
</table>

## Skills
***
<ul class="cv-skills">
  <li><i class="fa fa-code" aria-hidden="true"></i> <strong>Programming</strong> Python, TypeScript</li>
  <li><i class="fa fa-book" aria-hidden="true"></i> <strong>Libraries</strong> Pytorch, Transformers, LangChain, LangGraph</li>
  <li><i class="fa fa-laptop" aria-hidden="true"></i> <strong>Operating Systems</strong> Linux and other UNIX variants, Microsoft Windows</li>
  <li><i class="fa fa-sync" aria-hidden="true"></i> <strong>Agile Methodologies</strong> Scrum and Kanban</li>
  <li><i class="fa fa-language" aria-hidden="true"></i> <strong>Languages</strong> French (Native), English (Full Professional Proficiency)</li>
</ul>

## Publications
***
<ul class="cv-list">{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Teaching
***
<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-chalkboard-teacher"></i> Data Structures and Fundamental Algorithms</th>
         <th>Nov. 2019 – 2021</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td>University of Toulouse III - Paul Sabatier</td>
        <td>Toulouse, France</td>
      </tr>
      <tr>
         <td colspan="2">Undergraduate course (Semester I), taught in French.</td>
      </tr>
   </tbody>
</table>

<table class="heatMap">
   <thead>
      <tr>
         <th><i class="fa fa-chalkboard-teacher"></i> Database Programming and administration</th>
         <th>Mar. 2020 – 2021</th>
      </tr>
   </thead>
   <tbody>
      <tr>
        <td>University of Toulouse III - Paul Sabatier</td>
        <td>Toulouse, France</td>
      </tr>
      <tr>
         <td colspan="2">Undergraduate course (Semester II), taught in French.</td>
      </tr>
   </tbody>
</table>

## Hobbies
***
<ul class="cv-hobbies">
  <li>Reading and gaming (with a strong interest in horror)</li>
  <li>Drawing and photography</li>
  <li>Bouldering</li>
</ul>
