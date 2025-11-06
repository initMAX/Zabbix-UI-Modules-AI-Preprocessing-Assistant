<div align=center>
    <h1>
        🔒 PRO Version Available
    </h1>
</div>

This is a **PRO-only** product. The full version with all features is available through initMAX PRO subscription.

For more information about initMAX PRO, please visit: [https://www.initmax.com/eshop/](https://www.initmax.com/eshop/)

---


<div align="center">
    <a href="http://www.initmax.com"><img src="./.readme/logo/initMAX_banner.png" alt="initMAX Logo"></a>
    <h3>
        <span>
            Honesty, diligence and MAXimum knowledge of our products is our standard.
        </span>
    </h3>
    <h3>
        <a href="https://www.linkedin.com/company/initmax/">
            <img alt="Static Badge" src="./.readme/logo/linkedin.png" height="32">
        </a>&nbsp;&nbsp;&nbsp;
        <a href="https://www.youtube.com/@initmax1">
            <img alt="Static Badge" src="./.readme/logo/youtube.png" height="32">
        </a>&nbsp;&nbsp;&nbsp;
        <a href="https://www.facebook.com/initmax">
            <img alt="Static Badge" src="./.readme/logo/facebook.png" height="32">
        </a>&nbsp;&nbsp;&nbsp;
        <a href="https://www.instagram.com/initmax/">
            <img alt="Static Badge" src="./.readme/logo/instagram.png" height="32">
        </a>&nbsp;&nbsp;&nbsp;
        <a href="https://x.com/initmax">
            <img alt="Static Badge" src="./.readme/logo/x.png" height="32">
        </a>&nbsp;&nbsp;&nbsp;
        <a href="https://github.com/initmax">
            <img alt="Static Badge" src="./.readme/logo/github.png" height="32">
        </a>
    </h3>
</div>
<br>

---
---

<br>
<br>
<div align="center">
    <h1>
        AI Preprocessing Assistant
    </h1>
    <h4><i>
        This AI-powered module helps Zabbix users design optimal preprocessing steps by suggesting appropriate data transformation sequences based on provided requirements.
    </i></h4>
    <br><br>
    <img alt="Static Badge" src="https://img.shields.io/badge/Required%20Zabbix%20version-7.0-red">
    <img alt="Static Badge" src="https://img.shields.io/badge/Required%20php%20version-8.0-blue">
    <br><br>
    <img src="./.readme/screen/Preprocessing_Assistant.png" width="600">
</div>
<br>
<br>

## Description
This module helps Zabbix users determine appropriate preprocessing steps by suggesting optimal configurations based on provided input data samples and desired output requirements. Users specify their input data characteristics and desired results, and the AI assistant proposes suitable preprocessing steps to achieve the requested data transformation. By leveraging this AI assistant, users can more efficiently design preprocessing rules that match their specific data processing needs.

<div align="center">
    <img src="./.readme/screen/PreprocessingAssistant_overview.png" width="1000">
</div>

<!-- *********************************************************************************************************************************** -->
<br>

## Key features
This AI-powered module enhances Zabbix by assisting with preprocessing configuration based on user requirements. It helps evaluate input data samples and desired output formats, suggesting appropriate preprocessing steps based on the user's specific needs.

The assistant is designed for user-friendly operation, allowing easy integration with various AI models. Users can connect it to OpenAI's API or other custom models with compatible APIs, such as GPT4ALL, providing flexibility in AI backends.

A standout feature is the ability to customize the system prompt used to initialize the assistant. This allows users to tailor the AI's suggestions and behavior to their specific preprocessing needs and scenarios, enhancing its effectiveness in transforming data into the required format.

<!-- *********************************************************************************************************************************** -->
<br>

## Administration
The AI Preprocessing Assistant's administration section is accessible through Zabbix menu: Administration → AI general → AI Preprocessing Assistant. This area is exclusively available to users with SuperAdmin privileges, ensuring secure management of the AI module.

In this section, SuperAdmins can configure essential settings for the AI assistant. These include selecting between OpenAI and custom AI services, setting up API endpoints, choosing AI models, and defining both system and first prompts. The system prompt establishes the assistant's core behavior, while the first prompt handles the initialization of each session with item details, input data samples, and initial preprocessing requirements. These configurations allow for tailoring the AI's functionality to best fit the organization's specific data processing needs within Zabbix.

<div align="center">
    <img src="./.readme/screen/Preprocessing_Assistant_administration.png" width="400">
</div>

<!-- *********************************************************************************************************************************** -->
<br>

## System prompt customization
The AI preprocessing assistant's behavior and effectiveness are fundamentally shaped by three interrelated components: the system prompt, current input, and history in current session. Each preprocessing suggestion represents a synthesis of these elements, with the system prompt serving as the foundational layer that guides how the AI understands and recommends preprocessing steps.

What makes the system prompt particularly powerful is its ability to establish the core framework for how the AI operates when suggesting preprocessing operations. Whether analyzing data patterns, recommending transformation steps, or providing preprocessing chains, the AI's approach to preprocessing design is directly influenced by the instructions and context provided in its system prompt.

While we provide a carefully tested default system prompt optimized for common preprocessing scenarios, the ability to customize this prompt is a key feature of our solution. Every administrator can tailor the AI's preprocessing recommendations to better align with their specific data handling requirements and preprocessing patterns. However, it's important to understand that modifying the system prompt requires careful consideration - while our default prompt has been extensively tested, the effectiveness of preprocessing suggestions can be highly sensitive to both the specific LLM model used and subtle details in the system prompt configuration.

<div align="center">
    <img src="./.readme/screen/Preprocessing_Assistant_prompt.png" width="400">
</div>

<br><br>
<div align="center">
    <a href="https://www.initmax.com/wiki/ai-preprocessing-assistant-2/">
        <img alt="wiki" src="./.readme/logo/wiki.png" height="32"><br>
        <b>Documentation</b><br>
        <img alt="arrow" src="./.readme/logo/arrow.png" height="32">
    </a>
</div>
<br>
<br>

---
---

<br>
<div align="center">
    <a href="https://www.initmax.com/">
        <img alt="web" src="./.readme/logo/web.png" height="32"> initMAX.com
    </a>&nbsp;&nbsp;&nbsp;
    <a href="tel:+420800244442">
        <img alt="phone" src="./.readme/logo/phone.png" height="32"> +420800244442
    </a>&nbsp;&nbsp;&nbsp;
    <a href="mailto:info@initmax.com">
        <img alt="mail" src="./.readme/logo/mail.png" height="32"> info@initmax.com
    </a>
    <br><br><br>
    <a href="https://www.linkedin.com/company/initmax/">
        <img alt="linkedin" src="./.readme/logo/linkedin.png" height="32">
    </a>&nbsp;
    <a href="https://www.youtube.com/@initmax1">
        <img alt="youtube" src="./.readme/logo/youtube.png" height="32">
    </a>&nbsp;
    <a href="https://www.facebook.com/initmax">
        <img alt="facebook" src="./.readme/logo/facebook.png" height="32">
    </a>&nbsp;
    <a href="https://www.instagram.com/initmax/">
        <img alt="instagram" src="./.readme/logo/instagram.png" height="32">
    </a>&nbsp;
    <a href="https://x.com/initmax">
        <img alt="x" src="./.readme/logo/x.png" height="32">
    </a>&nbsp;
    <a href="https://github.com/initmax">
        <img alt="github" src="./.readme/logo/github.png" height="32">
    </a><br><br><br>
    <a><img src="./.readme/logo/zabbix-premium-partner.png" alt="Zabbix premium partner" width="80"></a>&nbsp;&nbsp;&nbsp;
    <a><img src="./.readme/logo/zabbix-certified-trainer.png" alt="Zabbix certified trainer" width="80"></a>
    <br><br><br>
    <a>
        <img src="./.readme/logo/agplv3.png" alt="agplv3" width="100">
    </a>
</div>