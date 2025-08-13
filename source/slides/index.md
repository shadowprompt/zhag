comments: true
title: 配套课件
date: 2022-10-26 09:23:04
---

### 《智慧农业概论》配套PPT

<script>
    function _zhagTrack(id) {
       window.LA?.track('download', {[id]: new Date().toLocaleString()});
       window._hmt?.push(['_trackEvent', 'download', 'click', id]);
    }

    // 确保 showDownloadModal 函数在页面中可用
    function showDownloadModal(fileName, downloadUrl, trackId) {
        // 检查全局函数是否已定义（来自主题模板）
        if (typeof window.showDownloadModalFromTheme === 'function') {
            window.showDownloadModalFromTheme(fileName, downloadUrl, trackId);
        } else {
            // 如果主题函数还没加载，等待一下再调用
            setTimeout(() => {
                if (typeof window.showDownloadModalFromTheme === 'function') {
                    window.showDownloadModalFromTheme(fileName, downloadUrl, trackId);
                } else {
                    console.error('下载功能未加载完成，请刷新页面重试');
                    alert('下载功能未加载完成，请刷新页面重试');
                }
            }, 500);
        }
    }
</script>

<!-- 模态框 -->
<div id="modalOverlay" class="download-modal-overlay"></div>
<div id="downloadModal" class="download-modal">
    <h3>下载信息收集</h3>
    <form id="downloadForm">
        <div class="download-form-group">
            <label for="userName">姓名 *</label>
            <input type="text" id="userName" name="userName" required>
        </div>
        <div class="download-form-group">
            <label for="userOrganization">单位 *</label>
            <input type="text" id="userOrganization" name="userOrganization" required>
        </div>
        <div class="download-form-group">
            <label for="userProfession">职业 *</label>
            <select id="userProfession" name="userProfession" required>
                <option value="">请选择职业</option>
                <option value="学生">学生</option>
                <option value="教师">教师</option>
                <option value="研究人员">研究人员</option>
                <option value="农业从业者">农业从业者</option>
                <option value="企业员工">企业员工</option>
                <option value="政府工作人员">政府工作人员</option>
                <option value="其他">其他</option>
            </select>
        </div>
        <div class="download-modal-buttons">
            <button type="button" class="download-btn download-btn-primary" onclick="handleDownload()">确认下载</button>
            <button type="button" class="download-btn download-btn-secondary" onclick="closeModal()">取消</button>
        </div>
    </form>
</div>

- 智慧农业概论-第一章-绪论-202210 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第一章-绪论-202210.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E4%B8%80%E7%AB%A0-%E7%BB%AA%E8%AE%BA-202210.pptx', 'chapter01')" href="javascript:void(0)">下载</a>
- 智慧农业概论-第二章-智慧农业的支撑技术-202210 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第二章-智慧农业的支撑技术-202210.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E4%BA%8C%E7%AB%A0-%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E7%9A%84%E6%94%AF%E6%92%91%E6%8A%80%E6%9C%AF-202210.pptx', 'chapter02')" href="javascript:void(0)">下载</a>
- 智慧农业概论-第三章-智能种植决策与执行-202210 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第三章-智能种植决策与执行-202210.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E4%B8%89%E7%AB%A0-%E6%99%BA%E8%83%BD%E7%A7%8D%E6%A4%8D%E5%86%B3%E7%AD%96%E4%B8%8E%E6%89%A7%E8%A1%8C-202210.pptx', 'chapter03')" href="javascript:void(0)">下载</a>
- 智慧农业概论-第四章-农作物生长智能检测-202209 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第四章-农作物生长智能检测-202209.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E5%9B%9B%E7%AB%A0-%E5%86%9C%E4%BD%9C%E7%89%A9%E7%94%9F%E9%95%BF%E6%99%BA%E8%83%BD%E6%A3%80%E6%B5%8B-202209.pptx', 'chapter04')" href="javascript:void(0)">下载</a>
- 智慧农业概论-第五章-智慧果园-202210 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第五章-智慧果园-202210.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E4%BA%94%E7%AB%A0-%E6%99%BA%E6%85%A7%E6%9E%9C%E5%9B%AD-202210.pptx', 'chapter05')" href="javascript:void(0)">下载</a>
- 智慧农业概论-第六章-智能化植物工厂-202210 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第六章-智能化植物工厂-202210.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E5%85%AD%E7%AB%A0-%E6%99%BA%E8%83%BD%E5%8C%96%E6%A4%8D%E7%89%A9%E5%B7%A5%E5%8E%82-202210.pptx', 'chapter06')" href="javascript:void(0)">下载</a>
- 智慧农业概论-第七章-智慧畜牧-202210 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第七章-智慧畜牧-202210.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E4%B8%83%E7%AB%A0-%E6%99%BA%E6%85%A7%E7%95%9C%E7%89%A7-202210.pptx', 'chapter07')" href="javascript:void(0)">下载</a>
- 智慧农业概论-第八章-智慧渔业-202210 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第八章-智慧渔业-202210.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E5%85%AB%E7%AB%A0-%E6%99%BA%E6%85%A7%E6%B8%94%E4%B8%9A-202210.pptx', 'chapter08')" href="javascript:void(0)">下载</a>
- 智慧农业概论-第九章-智慧农产品运营-202210 (pptx)   <a onclick="showDownloadModal('智慧农业概论-第九章-智慧农产品运营-202210.pptx', 'https://wp-img.daozhao.com/zhag/%E6%99%BA%E6%85%A7%E5%86%9C%E4%B8%9A%E6%A6%82%E8%AE%BA-%E7%AC%AC%E4%B9%9D%E7%AB%A0-%E6%99%BA%E6%85%A7%E5%86%9C%E4%BA%A7%E5%93%81%E8%BF%90%E8%90%A5-202210.pptx', 'chapter09')" href="javascript:void(0)">下载</a>

> - <span style="font-size: small; "> PPT制作者：全体编写人员</span>
> - <span style="font-size: small; "> PPT显示比例：宽屏16:9</span>
> - <span style="font-size: small; "> PPT软件版本：Microsoft 365</span>

### 《农业大数据》
#### 配套PPT
- 第1章 农业大数据概述 熊航 (pptx)  <a onclick="showDownloadModal('第1章 农业大数据概述 熊航.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第1章 农业大数据概述 熊航.pptx', 'chapter01')" href="javascript:void(0)">下载</a>
- 第2章 遥感大数据 胡琼 (pptx)  <a onclick="showDownloadModal('第2章 遥感大数据 胡琼.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第2章 遥感大数据 胡琼.pptx', 'chapter02')" href="javascript:void(0)">下载</a>
- 第3章 物联网数据 林涛 (pptx)  <a onclick="showDownloadModal('第3章 物联网数据 林涛.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第3章 物联网数据 林涛.pptx', 'chapter03')" href="javascript:void(0)">下载</a>
- 第4章 台站监测数据 冯晓龙 (pptx)  <a onclick="showDownloadModal('第4章 台站监测数据 冯晓龙.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第4章 台站监测数据 冯晓龙.pptx', 'chapter04')" href="javascript:void(0)">下载</a>
- 第5章 互联网数据 熊涛 (pptx)  <a onclick="showDownloadModal('第5章 互联网数据 熊涛.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第5章 互联网数据 熊涛.pptx', 'chapter05')" href="javascript:void(0)">下载</a>
- 第6章 政府统计数据 张晓恒 (pptx)  <a onclick="showDownloadModal('第6章 政府统计数据 张晓恒.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第6章 政府统计数据 张晓恒.pptx', 'chapter06')" href="javascript:void(0)">下载</a>
- 第7章 农户调查数据 田旭 (pptx)  <a onclick="showDownloadModal('第7章 农户调查数据 田旭.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第7章 农户调查数据 田旭.pptx', 'chapter07')" href="javascript:void(0)">下载</a>
- 第8章 众包数据 吕佳乐 (pptx)  <a onclick="showDownloadModal('第8章 众包数据 吕佳乐.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第8章 众包数据 吕佳乐.pptx', 'chapter08')" href="javascript:void(0)">下载</a>
- 第9章 作物大数据 李林等 (pptx)  <a onclick="showDownloadModal('第9章 作物大数据 李林等.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第9章 作物大数据 李林等.pptx', 'chapter09')" href="javascript:void(0)">下载</a>
- 第10章 园艺大数据 黄远 (pptx)  <a onclick="showDownloadModal('第10章 园艺大数据 黄远.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第10章 园艺大数据 黄远.pptx', 'chapter10')" href="javascript:void(0)">下载</a>
- 第11章 畜牧业大数据 周远飞 (pptx)  <a onclick="showDownloadModal('第11章 畜牧业大数据 周远飞.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第11章 畜牧业大数据 周远飞.pptx', 'chapter11')" href="javascript:void(0)">下载</a>
- 第12章 渔业大数据 马贺 (pptx)  <a onclick="showDownloadModal('第12章 渔业大数据 马贺.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第12章 渔业大数据 马贺.pptx', 'chapter12')" href="javascript:void(0)">下载</a>
- 第13章 农产品供应链大数据 洪宪培 (pptx)  <a onclick="showDownloadModal('第13章 农产品供应链大数据 洪宪培.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第13章 农产品供应链大数据 洪宪培.pptx', 'chapter13')" href="javascript:void(0)">下载</a>
- 第14章 农产品市场大数据 熊涛 (pptx)  <a onclick="showDownloadModal('第14章 农产品市场大数据 熊涛.pptx', 'https://wp-img.daozhao.com/zhag/农业大数据PPT课件/第14章 农产品市场大数据 熊涛.pptx', 'chapter14')" href="javascript:void(0)">下载</a>

#### 思考题参考答案
- 第1章 农业大数据概述 思考题参考答案 (docx)  <a onclick="showDownloadModal('第1章 农业大数据概述 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第1章 农业大数据概述 思考题参考答案.docx', 'chapter01')" href="javascript:void(0)">下载</a>
- 第2章 遥感大数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第2章 遥感大数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第2章 遥感大数据 思考题参考答案.docx', 'chapter02')" href="javascript:void(0)">下载</a>
- 第3章 物联网数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第3章 物联网数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第3章 物联网数据 思考题参考答案.docx', 'chapter03')" href="javascript:void(0)">下载</a>
- 第4章 台站监测数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第4章 台站监测数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第4章 台站监测数据 思考题参考答案.docx', 'chapter04')" href="javascript:void(0)">下载</a>
- 第5章 互联网数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第5章 互联网数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第5章 互联网数据 思考题参考答案.docx', 'chapter05')" href="javascript:void(0)">下载</a>
- 第6章 政府统计数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第6章 政府统计数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第6章 政府统计数据 思考题参考答案.docx', 'chapter06')" href="javascript:void(0)">下载</a>
- 第7章 农户调查数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第7章 农户调查数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第7章 农户调查数据 思考题参考答案.docx', 'chapter07')" href="javascript:void(0)">下载</a>
- 第8章 众包数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第8章 众包数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第8章 众包数据 思考题参考答案.docx', 'chapter08')" href="javascript:void(0)">下载</a>
- 第9章 作物大数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第9章 作物大数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第9章 作物大数据 思考题参考答案.docx', 'chapter09')" href="javascript:void(0)">下载</a>
- 第10章 园艺大数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第10章 园艺大数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第10章 园艺大数据 思考题参考答案.docx', 'chapter10')" href="javascript:void(0)">下载</a>
- 第11章 畜牧业大数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第11章 畜牧业大数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第11章 畜牧业大数据 思考题参考答案.docx', 'chapter11')" href="javascript:void(0)">下载</a>
- 第12章 渔业大数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第12章 渔业大数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第12章 渔业大数据 思考题参考答案.docx', 'chapter12')" href="javascript:void(0)">下载</a>
- 第13章 农产品供应链大数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第13章 农产品供应链大数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第13章 农产品供应链大数据 思考题参考答案.docx', 'chapter13')" href="javascript:void(0)">下载</a>
- 第14章 农产品市场大数据 思考题参考答案 (docx)  <a onclick="showDownloadModal('第14章 农产品市场大数据 思考题参考答案.docx', 'https://wp-img.daozhao.com/zhag/农业大数据思考题参考答案/第14章 农产品市场大数据 思考题参考答案.docx', 'chapter14')" href="javascript:void(0)">下载</a>
