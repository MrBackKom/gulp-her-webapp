# gulp-her-webapp
Her是基于gulp编译工具和smarty plugin开发的一套前端集成解决方案。实现了基于smarty运行时和前端Bigpipe框架的分块输出和按需渲染，极大的优化了前端性能。  Her定义了一套开发规范，通过编写gulp-her插件实现了一套完整的自动化构建平台。运行时包括后端smarty以及前端JS库，通过对页面进行细粒度分块，收集区块的dom、js、css等资源，后端controller控制按需输出，前端Bigpipe框架按需渲染，实现最大限度的前端性能优化。