<template>
  <div class="workContainer" id="workExperience">
    <h1>WORK EXPERIENCE</h1>

    <div class="workDescription">
      A reversed progression of roles across senior platform engineering focused on test infrastructure and distributed systems, QA engineering, and customer-facing support.
    </div>

    <!-- ================= FANATICS (NEWEST) ================= -->
    <div>
      <div class="jobHeader">Fanatics Betting and Gaming</div>

      <div class="workSubContainer">
        <strong>Senior Software Engineer</strong> · January 2024 - May 2026

        <div class="tree">

          <!-- 1 -->
          <details class="treeNode" open>
            <summary>Cloud Infrastructure, DevOps & Observability</summary>
            <ul>
              <li>Deployed containerized services using Docker, AWS ECR & S3, Kubernetes, and Terraform, enabling scalable cloud-based execution of service validation workloads.</li>
              <li>Established infrastructure to enable framework integration with CI/CD pipelines to enforce automated validation of service behavior prior to release</li>
              <li>Implemented custom integrations with ReportPortal and later Datadog, streaming real-time test logs to centralized, accessible observability platforms</li>
              <li>Created a React dashboard for test framework results backed by an AWS RDS SQL database</li>
            </ul>
          </details>

          <!-- 2 -->
          <details class="treeNode" open>
            <summary>Backend Engineering & Platform Development</summary>
            <ul>
              <li>Built and maintained Python service to integrate with internal backend platform, simplifying data generation and manipulation</li>
              <li>Converted Python-based backend service into a reusable Kotlin library supporting API validation, request orchestration, and response verification across multiple services</li>
              <li>Developed BFF service layer integrations</li>
              <li>Created service health monitoring for client-facing systems</li>
              <li>Owned and evolved custom Java testing platform used to validate Kotlin functionality and client-facing service layers and APIs, ensuring end-to-end reliability of high-traffic services</li>
            </ul>
          </details>

          <!-- 3 -->
          <details class="treeNode" open>
            <summary>Test Automation & Engineering Excellence</summary>
            <ul>
              <li>Increased automated P0 test scenarios by 1,150% (12 to 150), significantly improving confidence in service-layer changes and deployments</li>
              <li>Created a Claude Skill to transcode existing automated tests into Kotlin while preserving 1:1 functionality</li>
              <li>Implemented mocking and simulation layers to emulate upstream dependencies and improve CI reliability</li>
            </ul>
          </details>

        </div>
      </div>
    </div>

    <!-- ================= URBN ================= -->
    <div>
      <div class="jobHeader">URBN</div>

      <div class="workSubContainer">
        <strong>Mobile QA Engineer</strong> · April 2021 - January 2024

        <ul>
          <li>Executed manual testing for mobile retail applications across feature releases and bug fixes</li>
          <li>Owned monthly full-app regression testing cycles to validate release stability</li>
          <li>Expanded and maintained structured QA testing procedures and documentation</li>
          <li>Extracted test coverage requirements from GitHub pull requests and feature specs</li>
          <li>Identified, documented, and communicated defects including HTTP-level debugging and proxy analysis</li>
          <li>Collaborated in Agile standups, planning sessions, and feature refinement meetings</li>
          <li>Contributed early exploration into automated regression testing strategies</li>
        </ul>
      </div>
    </div>

    <!-- ================= AWEBER ================= -->
    <div>
      <div class="jobHeader">AWeber</div>

      <div class="workSubContainer">
        <strong>Customer Solutions Specialist (Tier IV)</strong> · June 2017 - April 2021

        <ul>
          <li>Served as liaison between end users and engineering teams, helping influence product decisions from a customer perspective</li>
          <li>Contributed incremental improvements to React and Redux-based features</li>
          <li>Deployed bug fixes in legacy PHP systems</li>
          <li>Participated in Agile Scrum ceremonies and cross-functional planning sessions</li>
          <li>Generated weekly product-wide bug reports for leadership visibility</li>
          <li>Triaged and communicated product outages and resolution updates to impacted customers</li>
          <li>Maintained and expanded a customer-facing knowledge base (100+ articles)</li>
          <li>Shadowed engineering teams during active feature development cycles</li>
        </ul>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'WorkExperience'
}
</script>

<style scoped>
#workExperience {
  scroll-margin-top: 90px; /* match your menu bar height */
}

.workContainer {
  display: flex;
  flex-direction: column;
  margin: 0 auto 150px;
}

.workContainer h1 {
  margin: 0 auto 25px;
  font-size: 50px;
}

.workDescription {
  width: 55%;
  font-size: 25px;
  text-align: center;
  margin: 0 auto 45px;
  line-height: 1.7;
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
  padding: 20px;
}

/* Job Header */
.jobHeader {
  font-size: 35px;
  color: #2ea44f;
  background-color: rgb(211, 253, 211);
  border-radius: 25px;
  width: fit-content;
  margin: 50px 0 10px 12%;
  padding: 10px;
}

/* Main card */
.workSubContainer {
  margin: auto;
  width: 75%;
  border-radius: 25px;
  border: 2px solid #2ea44f;
  background-color: rgb(244, 255, 244);
  padding: 20px;
  font-size: 20px;
  line-height: 1.7;
}

/* ================= TREE UI ================= */

.tree {
  margin-top: 15px;
}

.treeNode {
  background: white;
  border: 1px solid rgba(46, 164, 79, 0.4);
  border-radius: 16px;
  margin-bottom: 12px;
  padding: 10px 14px;
  transition: all 0.25s ease;
}

.treeNode summary {
  cursor: pointer;
  font-weight: 600;
  font-size: 18px;
  color: #2ea44f;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.treeNode summary::-webkit-details-marker {
  display: none;
}

.treeNode summary::after {
  content: "▸";
  transition: transform 0.2s ease;
}

.treeNode[open] summary::after {
  transform: rotate(90deg);
}

.treeNode ul {
  margin: 12px 0 0 18px;
  padding-left: 18px;
}

.treeNode li {
  margin-bottom: 10px;
}

.treeNode:hover {
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.08);
  transform: translateY(-1px);
}

/* ================= MOBILE ================= */

@media only screen and (max-width: 600px) {
  .workDescription {
    width: 75%;
  }

  .jobHeader {
    margin-left: 5%;
  }

  .workSubContainer {
    width: 90%;
  }
}
</style>