---
layout: page
title: Projects
permalink: /projects/
description: Most of my machine learning or symbolic AI projects in one place !
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---

<div class="projects">

  <div class="row row-cols-1 row-cols-md-2">

    <!-- Project 1 -->
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">

          <h3 class="card-title">
            2026 -- Implicit Layer in a Graph Neural Network for the Power Grid
          </h3>

          <div class="mb-3">
            <span class="badge font-weight-normal">JAX</span>
            <span class="badge font-weight-normal">Implicit Layer</span>
            <span class="badge font-weight-normal">Graph Neural Networks</span>
            <span class="badge font-weight-normal">Deep Equilibrium Models</span>
          </div>

          <p><em>RTE &amp; Mines de Paris</em></p>

          <p class="card-text">
            Designing and implementing an implicit layer using deep equilibrium
            models from scratch in JAX. The layer is integrated into a larger
            architecture including an encoder and a decoder.
          </p>

          <p class="card-text">
            <strong>Results:</strong> <i> Ongoing</i> -- forward and backward passes are
            working; training is in progress.
          </p>

        </div>
      </div>
    </div>


    <!-- Project 2 -->
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">

          <h3 class="card-title">
            2026 -- Explainable Resource Allocation and Data Disclosure
          </h3>

          <div class="mb-3">
            <span class="badge font-weight-normal">SAT-solver</span>
            <span class="badge font-weight-normal">Explainable AI</span>
            <span class="badge font-weight-normal">Minimal Unsatisfiable Set</span>
          </div>

          <p>
            <em>
              Paris-Saclay University, CentraleSupélec,
              Laboratory of Mathematics and Computer Science (MICS)
            </em>
          </p>

          <p>
            <strong>Link:</strong>
            <a href="{{ '/assets/pdf/Trade_off_between_Privacy_and_Explainability_in_House_Allocation_problems.pdf' | relative_url }}">
              Research report
            </a>
          </p>

          <p class="card-text">
            By encoding allocation, preferences, and fairness axioms into
            <strong>Boolean Satisfiability</strong> (SAT) formulas, local
            counterfactual queries are answered by extracting
            <strong>Minimal Unsatisfiable Subsets</strong> (MUSes).
          </p>

          <p class="card-text">
            Quantitative metrics were introduced to measure the degree of data
            disclosure induced by an explanation, based on the reduction of
            the querying agent's posterior compatible set of preference
            profiles.
          </p>

          <p class="card-text">
            <strong>Results:</strong> MUS explanations are rarely possible and,
            when they are, induce a relative data disclosure of at least 95%
            in the studied configurations.
          </p>

        </div>
      </div>
    </div>


    <!-- Project 3 -->
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">

          <h3 class="card-title">
            2026 -- Reinforcement Learning for Autonomous Driving
          </h3>

          <div class="mb-3">
            <span class="badge font-weight-normal">Gymnasium</span>
            <span class="badge font-weight-normal">DQN</span>
            <span class="badge font-weight-normal">Double DQN</span>
            <span class="badge font-weight-normal">PER</span>
            <span class="badge font-weight-normal">PyTorch</span>
            <span class="badge font-weight-normal">Behavioural Analysis</span>
          </div>

          <p>
            <strong>Links:</strong>
            <a href="{{ '/assets/pdf/RL_report_highway.pdf' | relative_url }}">
              Research report
            </a>
            ·
            <a href="https://github.com/Nicolas2412/rl-highway">
              Project repository
            </a>
          </p>

          <p class="card-text">
            In the context of a group project using the Gymnasium
            <em>highway-v0</em> environment, I implemented a Double DQN and
            conducted a performance analysis of trained agents.
          </p>

          <p class="card-text">
            I evaluated the impact of algorithmic choices through ablation
            studies, <strong> investigating whether systematic hyperparameter
            optimization can close the performance gap between a vanilla DQN
            and its algorithmic extensions, or whether architectural
            improvements provide independent gains.</strong>
          </p>

        </div>
      </div>
    </div>


    <!-- Project 4 -->
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">

          <h3 class="card-title">
            2026 -- Explainability in Linear Optimization
          </h3>

          <div class="mb-3">
            <span class="badge font-weight-normal">Gurobi</span>
            <span class="badge font-weight-normal">NetworkX</span>
          </div>

          <p>
            <strong>Link:</strong>
            <a href="https://github.com/SarahL-1720/linear-optimisation-sdp-project">
              GitHub repository
            </a>
          </p>

          <p class="card-text">
            Developed algorithms for generating (1-1), (1-m), (m-1), and mixed
            explanations in optimization problems.
          </p>

          <p class="card-text">
            The framework was applied to large-scale experiments on
            transportation and healthcare datasets, with a particular focus
            on studying the existence conditions of optimization-based
            explanations.
          </p>

        </div>
      </div>
    </div>


    <!-- Project 5 -->
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">

          <h3 class="card-title">
            2026 -- Graph Neural Networks: GCN vs GAT
          </h3>

          <div class="mb-3">
            <span class="badge font-weight-normal">PyTorch Geometric</span>
            <span class="badge font-weight-normal">GNN</span>
            <span class="badge font-weight-normal">Node2Vec</span>
            <span class="badge font-weight-normal">Ablation Study</span>
          </div>

          <p>
            <strong>Link:</strong>
            <a href="https://github.com/SarahL-1720/graph-analytics-ml">
              GitHub repository
            </a>
          </p>

          <p class="card-text">
            <strong> Investigated the architectural trade-offs between GCN and GAT </strong> for
            node classification and link prediction on large-scale graphs,
            including Git Web ML (37K nodes, 290K edges) and WikiOGB.
          </p>

          <p class="card-text">
            Hard negative sampling was implemented to address the false
            negative issue in link prediction evaluation.
          </p>

          <p class="card-text">
            <strong>Results:</strong> The best model, a 3-layer GCN with an MLP
            decoder, achieved 93.3% link prediction accuracy. The best
            classification model, a 2-layer GAT, reached 78.3% accuracy.
          </p>

        </div>
      </div>
    </div>


    <!-- Project 6 -->
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">

          <h3 class="card-title">
            2025 -- Freelance Project: Medical Data Cleaning and Filling
          </h3>

          <div class="mb-3">
            <span class="badge font-weight-normal">API SIRENE</span>
            <span class="badge font-weight-normal">Google Places API</span>
          </div>

          <p>
            <strong>Repository:</strong>
            <a href="https://github.com/SarahL-1720/SIRET-medical-companies-data-cleaning">
              GitHub repository
            </a>
          </p>

          <p class="card-text">
            Completed a 60,000-line database using SIRET and SIRENE data.
            Performed quality checks including address validation and hierarchy
            consistency.
          </p>

          <p class="card-text">
            <strong>Results:</strong> 83% completion rate.
          </p>

        </div>
      </div>
    </div>


    <!-- Project 7 -->
    <div class="col mb-4">
      <div class="card h-100">
        <div class="card-body">

          <h3 class="card-title">
            2025 -- Retrieval Augmented Chatbot
          </h3>

          <div class="mb-3">
            <span class="badge font-weight-normal">RAG</span>
            <span class="badge font-weight-normal">PyTorch</span>
            <span class="badge font-weight-normal">Streamlit</span>
          </div>

          <p>
            <em>European Central Bank</em>
          </p>

          <p>
            <strong>Link:</strong>
            <a href="https://gitlab.com/portfolio-sarah/rag_chatbot">
              GitLab repository
            </a>
          </p>

          <p class="card-text">
            Designed a <strong>Retrieval-Augmented Generation (RAG)</strong>
            assistant with a tailored chunking strategy. Benchmarked embedding
            retrieval against a TF-IDF baseline.
          </p>

          <p class="card-text">
            <strong>Results:</strong> A tool used by approximately 20 people to
            retrieve information from 13 internal reports of around 150 pages.
          </p>

        </div>
      </div>
    </div>

  </div>

</div>