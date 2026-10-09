# JiNanYuWen

暨南大学《中文》教材 PDF。

## 大文件合并

GitHub 单文件上限为 100MB，以下文件被拆分为多个 `.partNN` 分卷，下载后需合并：

czb3.pdf、czb4.pdf、czb5.pdf、czb6.pdf、初中1.pdf、初中2.pdf

**Windows (cmd):**

```
copy /b czb3.pdf.part00+czb3.pdf.part01+czb3.pdf.part02 czb3.pdf
```

**macOS / Linux / Git Bash:**

```
cat czb3.pdf.part* > czb3.pdf
```

其他文件同理。
