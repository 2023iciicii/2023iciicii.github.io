---
permalink: /Speech/
redirect_from:
  - /resume
---

{% include base_path %}
<div class="speech-container">
    <h1>Keynote / Invited Speech</h1>
    <div class="speeches">
        <div class="speech-column">
            <h2>2023</h2>
            <ul>
                <li><a href="talk4-1/">Prof. Dingfang Chen: Frontiers in Intelligent Manufacturing</a></li>
                <li><a href="talk4-2/">Prof. Kaushik Rajashekara: Current and Future Trends in Transportation Electrification</a></li>
                <li><a href="talk4-3/">Prof. Zengguang Hou: Intelligent Rehabilitation Technology Based on Brain-Computer Interface</a></li>
                <li><a href="talk4-4/">Prof. Haibin Zhu: Group Role Assignment with Constraints(GRA+): A New Category of Assignment Problems</a></li>
                <li><a href="talk4-5/">Prof. Lijie Li: Wireless Free Space Optical Communications</a></li>
                <li><a href="talk4-6/">Prof. Arturo Suman Bretas: Proactive Frequency Stability Scheme via Bayesian Filters and Synchrophasors</a></li>
                <li><a href="talk4-7/">Prof. Shuangbao Ma: Cloth Defect Detection Method Based on Deep Learning</a></li>
                <li><a href="talk4-8/">Prof. Junwei Zhou: Unified Syslog Anomaly Detection Using Deep Learning</a></li>
                <li><a href="talk4-9/">Prof. Leisheng Jin: Information Processing of Industrial Dynamics Systems Using Reservoir Computing</a></li>
            </ul>
        </div>
    </div>
</div>

<style>
  
.speeches {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; /* 使所有列居中对齐 */
    gap: 20px; /* 每列之间的间距 */
}

.speech-column {
    width: 50%; /* 设置每列宽度为 22%，以便能够容纳四列，并留出间隙 */
    box-sizing: border-box; /* 确保 padding 和 border 不影响整体宽度 */
    padding: 10px;
    background-color: #f9f9f9; /* 给每列添加背景色，使它们更明显 */
    text-align: center; /* 每列内文本居中 */
}

.speech-column h2 {
    font-size: 1.2em; /* 调整标题大小 */
    color: #2c3e50; /* 设置标题颜色 */
    margin-bottom: 12px; /* 与列表之间的间距 */
    text-align: center;
}

.speech-column ul {
    list-style-type: none;
    padding: 0;
}

.speech-column li {
    margin: 15px 0;
    padding: 20px;
    background-color: #f1f1f1;
    border: 1px solid #ddd;
    border-radius: 5px;
    height: 200px; /* 设置固定高度，确保每个框的大小一致 */
    display: flex;
    align-items: center; /* 使文字在框内垂直居中 */
    transition: transform 0.3s, box-shadow 0.3s;
}

.speech-column li:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.speech-column li a {
    text-decoration: none;
    color: #2980b9;
    font-weight: bold;
    text-align: center; /* 链接文字居中 */
    width: 100%;
}

.speech-column li a:hover {
    text-decoration: underline;
}


.speech-container {
    position: relative; /* 可选：如果不想保持相对定位，删除这行 */
    width: 100vw; /* 删除这一行，使容器不再强制占满整个视口宽度 */
    margin-left: calc(50% - 50vw); /* 删除这一行，取消强制容器宽度从页面边界开始 */
    padding: 30px;
    background-color: #ffffff;
    border-radius: 10px;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.speech-container h1 {
    font-size: 2em;
    color: #2c3e50;
    margin-bottom: 20px;
    text-align: center;
    position: sticky; /* 保持标题在页面顶部可见 */
    top: 0;
    background-color: #ffffff;
    padding: 20px;
    z-index: 10;
}
  
</style>
