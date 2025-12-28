# Pre-PHD-Seminar-Attachment

本文件夹用于存放 `Pre-PHD-Seminar` 文件夹中对应章节的相关资料，包括但不限于：
- 课程PPT演示文稿（.pptx）
- 参考文档（.pdf）
- 其他相关资源

每个章节的资料存放在对应的 `Chapter{N}/` 目录下，与主文件夹 `Pre-PHD-Seminar` 的章节结构一一对应。

---

## Project Structure
```
├── README.md                # 项目总览和章节索引
├── Chapter1/                # Chapter 1：Gradient Descent & Backpropagation
│   ├── *.pptx               # 章节相关参考资料(ppt、pdf)
│   ├── *.pdf
│   :           
├── Chapter2/                # 其他章节遵循相同结构
│   ├── *.pptx
│   ├── *.pdf
│   : 
├── ...
```

### 目录命名规范
1. **章节目录**：使用 `Chapter{N}/` 格式，其中 `{N}` 为章节编号（如 `Chapter1/`, `Chapter2/`）
2. **文件命名**：PPTX、PDF等文件的命名应准确概括其内容

### 添加新章节
- 在根目录下创建 `Chapter{N}/` 目录
- 在对应目录下存放本章节参考资料

### 版本控制建议
- 使用 Git 进行版本控制
- 提交信息格式：`<type>: Chapter{N} <description>`
- 大文件（PDF、大图片）考虑使用 Git LFS
