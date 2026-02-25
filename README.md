<div align="center">
  <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/via.fuckcustomtab.frisk/refs/heads/main/docs/hina.jpg" width="250" height="250" alt="Hina" />
  
  # FuckCustomTab
  **去他妈的应用内浏览器**
  <br>
[![GitHub](https://img.shields.io/badge/github-repo-blue?logo=github)](https://github.com/frisk1127/FuckCustomTab)
[![下载次数](https://img.shields.io/github/downloads/Xposed-Modules-Repo/via.fuckcustomtab.frisk/total?color=yellow)](https://github.com/Xposed-Modules-Repo/via.fuckcustomtab.frisk/releases)
  <p><strong>简体中文</strong> | <a href="#english">English</a></p>
</div>

---

## 作用
阻止浏览器跳转链接时使用应用内浏览器（ CustomTab ）

理论上支持所有使用 CustomTab 的浏览器

注: Via 已在 7.0.0 支持关闭 CustomTab 请使用 Via 内置选项 （ 设置 → 高级 → 禁用 Custom Tabs ）

### 已测试
| 浏览器 | 版本 |
| --- | --- |
| Via | 6.9.0 |
| Edge | 143.0.3650.139 |
| Chrome | 143.0.7499.192 |

## 如果不适配你的浏览器

如果本模块没有适配你使用的浏览器，欢迎 [提交 Issue](https://github.com/frisk1127/FuckCustomTab/issues)，我会尽快处理

<details>
<summary><strong>制作原因</strong></summary>

<p></p>

<p>
Via 在版本 6.9.0 适配了链接应用内打开 导致想要使用浏览器内置的下载管理器等页面需要再点击一个按钮跳转到 Via 非常繁琐
</p>

<p>
本模块用于移除此特性。
</p>

</details>

## 效果

| 使用前 | 使用后 |
| --- | --- |
| <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/via.fuckcustomtab.frisk/refs/heads/main/docs/before.jpg" alt="Before" width="380" /> | <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/via.fuckcustomtab.frisk/refs/heads/main/docs/after.jpg" alt="After" width="380" /> |

---

<a id="english"></a>

## English

### Purpose
Block browsers from opening links with in-app browsers (CustomTabs).

In theory, it supports all browsers that use CustomTabs.

Note: Since version 7.0.0, Via natively supports disabling Custom Tabs. Please use the built-in option (Settings → Advanced → Disable Custom Tabs).

### Tested
| Browser | Version |
| --- | --- |
| Via | 6.9.0 |
| Edge | 143.0.3650.139 |
| Chrome | 143.0.7499.192 |

## If it does not support your browser

If this module does not support your browser, feel free to [file an Issue](https://github.com/frisk1127/FuckCustomTab/issues). I will handle it as soon as possible.

<details>
<summary><strong>Why I made this</strong></summary>

<p></p>

<p>
Via added in-app link opening in version 6.9.0. To use the built-in download manager and similar pages, you must tap another button to jump to Via, which is very inconvenient.
</p>

<p>
This module removes that behavior.
</p>

</details>

## Result

| Before | After |
| --- | --- |
| <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/via.fuckcustomtab.frisk/refs/heads/main/docs/before.jpg" alt="Before" width="380" /> | <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/via.fuckcustomtab.frisk/refs/heads/main/docs/after.jpg" alt="After" width="380" /> |

## Stars
[![Stargazers over time](https://starchart.cc/frisk1127/FuckCustomTab.svg?background=%23FFFFFF&axis=%23333333&line=%236b63ff)](https://github.com/frisk1127/FuckCustomTab)










