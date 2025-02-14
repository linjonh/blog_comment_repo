# blog_comment_repo
save blog comments repository

# config comment
using [**giscus github app**](https://github.com/apps/giscus) to integrate coomment feature。

以下是完整的安装步骤：

---

## **1. 访问 `giscus` GitHub App**
打开 [giscus GitHub App](https://github.com/apps/giscus) 页面。

---

## **2. 安装 `giscus`**
点击 `Install`（安装），然后：
- **选择 GitHub 账号或组织**（如果你是个人博客，选择你的个人账号）。
- **选择要启用的仓库**（选择存放 Discussions 的仓库）。
- **点击 "Install"** 进行安装。

---

## **3. 确保 GitHub Discussions 已启用**
1. 进入你的 GitHub 仓库。
2. 在 `Settings` → `Features` 里找到 `Discussions`。
3. **启用 Discussions**（如果还未启用）。

---

## **4. 确保 Giscus 具有正确的权限**
在 GitHub App 权限管理页面：
- **检查 `giscus` 是否已安装到你的仓库**（在 `Installed GitHub Apps` 里查看）。
- **确保 `Read & write` 访问权限已授予 Discussions**。

---

## **5. 配置 Giscus**
**Last but not least（最后同样重要）**
1. **访问** [giscus.app](https://giscus.app/) 配置。
2. **选择仓库** 并 **生成新的 `<script>` 代码**。
3. **替换你网站中的 giscus 配置代码**。

---

完成以上步骤后，`giscus` 应该能正常运行，访客就可以评论了！🚀