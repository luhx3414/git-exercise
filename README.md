# Production-Ready Data Science Code Examples

**Code examples from the Production-Ready Data Science book by Khuyen Tran.把混乱的 Jupyter Notebook 变成生产级代码的结构化教程。14章覆盖 Git、模块化、测试、CI/CD、日志、数据验证——全部是你从数据科学转工程最需要的技能**

Enhance your data science workflow with scalable, production-ready practices through hands-on examples.

[🔗 **Get the Book**](https://codecut.ai/production-ready-data-science/?utm_source=github&utm_medium=production-ready-data-science-code&utm_campaign=main-readme)

## What You'll Gain

Transform your data science workflow with these production-ready skills:

- **📁 Organization**: Transform messy notebooks into organized, maintainable code
- **🔄 Reproducibility**: Create reproducible environments across teams and deployments  
- **🧪 Quality**: Write modular, reusable, and testable Python code
- **🔍 Testing**: Implement automated testing to catch bugs early
- **📊 Version Control**: Leverage version control for code and data integrity
- **🚀 Production**: Deploy bulletproof systems that scale

## Examples by Chapter

**Chapter 1-3: Foundation**
1. [Version Control](chapter1_version_control/) - Git workflows
2. [Dependency Management](chapter2_dependency_management/) - Environment setup  
3. [Modules & Packages](chapter3_modules_packages/) - Project organization

**Chapter 4-6: Code Quality**

4. [Variables](chapter4_variables/) - Clean code practices
5. [Functions](chapter5_functions/) - Function design
6. [Classes](chapter6_classes/) - Object-oriented programming

**Chapter 7-9: Testing & Operations**

7. [Unit Testing](chapter7_unit_testing/) - Automated testing
8. [Configuration Management](chapter8_configuration_management/) - Settings management
9. [Logging](chapter9_logging/) - Monitoring and debugging

**Chapter 10-11: Data**

10. [Data Validation](chapter10_data_validation/) - Input validation
11. [Data Version Control](chapter11_data_version_control/) - Dataset tracking

**Chapter 12-14: Production**

12. [Continuous Integration](chapter12_continuous_integration/) - Automated deployment
13. [Package Your Project](chapter13_package_your_project/) - Package distribution
14. [Notebooks in Production](chapter14_notebooks_in_production/) - Production notebooks

## Getting Started

### Fork and Clone

1. Click the "Fork" button at the top of this page
2. This creates your own copy at: `github.com/YOUR_USERNAME/production-ready-data-science-code`
3. Clone your fork:
```bash
git clone https://github.com/YOUR_USERNAME/production-ready-data-science-code.git
cd production-ready-data-science-code
```

### Prerequisites

- Python 3.10.11 or higher
- [uv](https://docs.astral.sh/uv/) - Fast Python package manager

### Install Dependencies

**Option A: Install Everything (Recommended)**
```bash
uv sync --all-groups
```

**Option B: Install Specific Chapters Only**
```bash
uv sync --group chapter7   # Testing examples
uv sync --group chapter9   # Logging examples  
uv sync --group chapter10  # Data validation
```

---

**Ready to get started?** Browse [examples above](#examples-by-chapter) or [get the book](https://codecut.ai/production-ready-data-science/?utm_source=github&utm_medium=production-ready-data-science-code&utm_campaign=bottom-cta)

**Author**: Khuyen Tran | **Website**: https://codecut.ai/
