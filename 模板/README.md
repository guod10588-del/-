# 📋 项目模板库

快速启动项目的模板、配置文件和代码骨架。

## 📂 目录结构

### 项目模板/

#### Python 项目
- `python-basic/` - 基础 Python 项目
- `python-web/` - Django/FastAPI 项目
- `python-cli/` - 命令行工具
- `python-package/` - Python 包发布

#### JavaScript/Node.js
- `nodejs-api/` - Node.js API 服务
- `nodejs-cli/` - 命令行工具
- `react-app/` - React 应用
- `vue-app/` - Vue 应用
- `nextjs-app/` - Next.js 应用

#### Go 项目
- `go-cli/` - Go 命令行工具
- `go-api/` - Go API 服务
- `go-package/` - Go 包

#### Docker
- `dockerfile-python/` - Python 容器
- `dockerfile-nodejs/` - Node.js 容器
- `docker-compose/` - 多容器编排

### 配置文件模板/

#### 前端配置
- `.prettierrc` - 代码格式化
- `.eslintrc.json` - JS 代码检查
- `tsconfig.json` - TypeScript 配置
- `vite.config.ts` - Vite 构建配置
- `webpack.config.js` - Webpack 配置

#### 后端配置
- `pyproject.toml` - Python 项目配置
- `setup.py` - Python 包配置
- `go.mod` - Go 模块配置
- `.env.example` - 环境变量模板

#### DevOps 配置
- `.github/workflows/` - GitHub Actions
- `.gitlab-ci.yml` - GitLab CI
- `docker-compose.yml` - 容器编排
- `Dockerfile` - Docker 镜像
- `kubernetes/` - K8s 配置

### 文档模板/

#### 项目文档
- `README.md` - 项目说明
- `CHANGELOG.md` - 版本记录
- `CONTRIBUTING.md` - 贡献指南
- `LICENSE` - 许可证

#### PR 和 Issue
- `.github/pull_request_template.md` - PR 模板
- `.github/issue_template/` - Issue 模板

## 🚀 快速使用

### 创建新项目

```bash
# 1. 选择合适的模板
cp -r 模板/项目模板/python-web my-project
cd my-project

# 2. 初始化 Git
git init
git add .
git commit -m "initial commit"

# 3. 安装依赖
pip install -r requirements.txt

# 4. 开始开发
```

### 应用配置文件

```bash
# 1. 复制配置模板
cp 模板/配置文件模板/.prettierrc .
cp 模板/配置文件模板/.eslintrc.json .

# 2. 根据项目需求��整
# 3. 在项目中使用
```

## 📝 模板清单

### Python 相关
- [ ] requirements.txt - 依赖列表
- [ ] pyproject.toml - 项目配置
- [ ] setup.py - 包配置
- [ ] Makefile - 常用命令
- [ ] pytest.ini - 测试配置

### JavaScript 相关
- [ ] package.json - 项目配置
- [ ] .npmrc - npm 配置
- [ ] tsconfig.json - TypeScript
- [ ] .eslintrc - 代码检查
- [ ] .prettierrc - 格式化

### 通用
- [ ] .gitignore - Git 忽略
- [ ] .editorconfig - 编辑器配置
- [ ] README.md - 项目说明
- [ ] LICENSE - 许可证
- [ ] docker-compose.yml - 容器编排

## 💡 自定义建议

1. **根据项目调整**
   - 修改依赖版本
   - 调整配置选项
   - 添加项目特定的内容

2. **保持一致性**
   - 遵循项目命名规范
   - 统一代码风格
   - 保持目录结构

3. **定期更新**
   - 更新过期的依赖
   - 采用新的最佳实践
   - 修复已知问题

## 📚 模板维护

### 何时更新模板
- 新版本发布
- 依赖包更新
- 最佳实践改变
- 发现新的工具

### 版本控制
- 记录模板版本
- 文档化更改内容
- 保留历史记录

## 🤝 贡献新模板

欢迎提交新的模板：
1. 创建清晰的目录结构
2. 包含完整的说明文档
3. 测试模板的可用性
4. 提供使用示例

---

**提示**: 定期检查模板的依赖版本和最佳实践