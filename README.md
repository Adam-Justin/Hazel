# Hazel Engine

 _    _           ____________ _        ______ _   _  _____ _____ _   _ ______ 
| |  | |   /\    |___  /  ____| |      |  ____| \ | |/ ____|_   _| \ | |  ____|
| |__| |  /  \      / /| |__  | |      | |__  |  \| | |  __  | | |  \| | |__   
|  __  | / /\ \    / / |  __| | |      |  __| | . ` | | |_ | | | | . ` |  __|  
| |  | |/ ____ \  / /__| |____| |____  | |____| |\  | |__| |_| |_| |\  | |____ 
|_|  |_/_/    \_\/_____|______|______| |______|_| \_|\_____|_____|_| \_|______|
                                                                               
                                                                               


## 12.21.2025

Add premake tools to auto genreate projects. Compire with the Cherno's premake version, you should use {COPYFILE} not {COPY} in your premake5.lua if you using a newer premake in 2025.
Run "GenreateProjects.bat" to auto genreate visual studio 2022 projects.

添加premake工具进行自动生成项目,如果你用的是2025新版premake的话,在premake5.lua中应该使用{COPYFILE}而不是{COPY},因为Cherno使用的premake版本是旧的.
运行GenreateProjects.bat脚本生成VisualStudio2022项目

## 12.08.2025

Add spdlog into project and set some macro about log level.

添加spdlog日志库并设置日志级别

## 12.07.2025

Init Hazel Engine and Sandbox project, add entry point.

初始化Hazel引擎和SandBox项目,并添加项目入口.