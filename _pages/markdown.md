---
permalink: /markdown/
title: "Markdown"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

{% include toc %}

## About Me

## 🎓 Academic & Work Experiences

#### My work experience

Waiting...

#### My study experience

<style>
.hybrid-timeline {
  position: relative;
  margin: 30px 0;
}

.timeline-connector {
  position: absolute;
  left: 15px;
  top: 0;
  bottom: 0;
  width: 2px;
  background: linear-gradient(to bottom, #3498db, #e74c3c, #9b59b6, #f39c12);
  z-index: 1;
}

.timeline-item {
  position: relative;
  z-index: 2;
  margin-bottom: 25px;
  transition: all 0.3s ease;
}

.timeline-item:hover {
  transform: translateY(-3px);
}

.timeline-node {
  position: relative;
  margin-right: 25px;
  flex-shrink: 0;
  transition: all 0.3s ease;
}

.timeline-item:hover .timeline-node {
  transform: scale(1.1);
}

.timeline-card {
  flex: 1;
  background: white;
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 5px 20px rgba(0,0,0,0.1);
  border-left: 4px solid #3498db;
  transition: all 0.3s ease;
  cursor: pointer;
}

.timeline-card:hover {
  box-shadow: 0 10px 30px rgba(0,0,0,0.15);
  transform: translateX(8px);
}

.time-badge {
  background: #3498db;
  color: white;
  padding: 6px 15px;
  border-radius: 20px;
  font-size: 0.85em;
  font-weight: bold;
  transition: all 0.3s ease;
}

.degree-badge {
  background: #ecf0f1;
  color: #2c3e50;
  padding: 4px 12px;
  border-radius: 15px;
  font-size: 0.8em;
  transition: all 0.3s ease;
}

.timeline-card:hover .time-badge {
  transform: scale(1.05);
  box-shadow: 0 3px 10px rgba(0,0,0,0.2);
}

.timeline-card:hover .degree-badge {
  background: #34495e;
  color: white;
}
</style>

<div class="hybrid-timeline">
  <!-- 时间轴连接线 -->
  <div class="timeline-connector"></div>

  <!-- 博士经历 -->
  <div class="timeline-item">
    <div style="display: flex; align-items: flex-start;">
      <div class="timeline-node">
        <div style="width: 32px; height: 32px; background: #3498db; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-weight: bold; font-size: 0.9em; box-shadow: 0 3px 10px rgba(52, 152, 219, 0.3);">🎓</div>
      </div>
      <div class="timeline-card" style="border-left-color: #3498db;">
        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 12px;">
          <span class="time-badge" style="background: #3498db;">2021.09 - Present</span>
          <span class="degree-badge">PhD Candidate</span>
        </div>
        <h4 style="margin: 0 0 8px 0; color: #2c3e50; font-size: 1.2em; transition: color 0.3s ease;">Zhengzhou University</h4>
        <div style="color: #7f8c8d; margin-bottom: 8px; font-weight: 500; transition: color 0.3s ease;">School of Computer Science and Artificial Intelligence</div>
        <div style="color: #3498db; font-weight: 600; transition: color 0.3s ease;">Software Engineering · Doctoral Program</div>
      </div>
    </div>
  </div>

  <!-- 硕士经历 -->
  <div class="timeline-item">
    <div style="display: flex; align-items: flex-start;">
      <div class="timeline-node">
        <div style="width: 32px; height: 32px; background: #e74c3c; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-weight: bold; font-size: 0.9em; box-shadow: 0 3px 10px rgba(231, 76, 60, 0.3);">📚</div>
      </div>
      <div class="timeline-card" style="border-left-color: #e74c3c;">
        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 12px;">
          <span class="time-badge" style="background: #e74c3c;">2018.09 - 2021.06</span>
          <span class="degree-badge">Master</span>
        </div>
        <h4 style="margin: 0 0 8px 0; color: #2c3e50; font-size: 1.2em; transition: color 0.3s ease;">Zhengzhou University</h4>
        <div style="color: #7f8c8d; margin-bottom: 8px; font-weight: 500; transition: color 0.3s ease;">School of Computer Science and Artificial Intelligence</div>
        <div style="color: #e74c3c; font-weight: 600; transition: color 0.3s ease;">Software Engineering · Master's Degree</div>
      </div>
    </div>
  </div>

  <!-- 访学经历 -->
  <div class="timeline-item">
    <div style="display: flex; align-items: flex-start;">
      <div class="timeline-node">
        <div style="width: 32px; height: 32px; background: #9b59b6; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-weight: bold; font-size: 0.9em; box-shadow: 0 3px 10px rgba(155, 89, 182, 0.3);">🌍</div>
      </div>
      <div class="timeline-card" style="border-left-color: #9b59b6;">
        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 12px;">
          <span class="time-badge" style="background: #9b59b6;">2021.07 - 2021.08</span>
          <span class="degree-badge">Exchange</span>
        </div>
        <h4 style="margin: 0 0 8px 0; color: #2c3e50; font-size: 1.2em; transition: color 0.3s ease;">University of Oulu</h4>
        <div style="color: #7f8c8d; margin-bottom: 8px; font-weight: 500; transition: color 0.3s ease;">Faculty of Information Technology and Electrical Engineering</div>
        <div style="color: #9b59b6; font-weight: 600; transition: color 0.3s ease;">Computer Technology · Visiting Scholar</div>
      </div>
    </div>
  </div>

  <!-- 本科经历 -->
  <div class="timeline-item">
    <div style="display: flex; align-items: flex-start;">
      <div class="timeline-node">
        <div style="width: 32px; height: 32px; background: #f39c12; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-weight: bold; font-size: 0.9em; box-shadow: 0 3px 10px rgba(243, 156, 18, 0.3);">📖</div>
      </div>
      <div class="timeline-card" style="border-left-color: #f39c12;">
        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 12px;">
          <span class="time-badge" style="background: #f39c12;">2014.09 - 2018.06</span>
          <span class="degree-badge">Bachelor</span>
        </div>
        <h4 style="margin: 0 0 8px 0; color: #2c3e50; font-size: 1.2em; transition: color 0.3s ease;">Zhengzhou University</h4>
        <div style="color: #7f8c8d; margin-bottom: 8px; font-weight: 500; transition: color 0.3s ease;">School of Information Engineering</div>
        <div style="color: #f39c12; font-weight: 600; transition: color 0.3s ease;">Computer Science and Technology · Bachelor's Degree</div>
      </div>
    </div>
  </div>
</div>


## 🔬 Research Interests

<div class="research-interests" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px; margin-top: 20px;">

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #3498db;">
<strong>Spatial Crowdsourcing</strong>
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #e74c3c;">
<strong>Big Data Management and Analysis</strong>
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #9b59b6;">
<strong>Applied AI & LLM</strong>
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #f39c12;">
<strong>Artificial Intelligence</strong>
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #1abc9c;">
<strong>Human-Machine Intelligence</strong>
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #d35400;">
<strong>Real-time Scheduling</strong>
</div>

<div style="background: #f8f9fa; padding: 15px; border-radius: 8px; border-left: 4px solid #27ae60;">
<strong>Visualization</strong>
</div>

</div>
