# Doxygen Documentation

## 1. Introduction

Doxygen is an open-source documentation generation tool used to automatically create documentation from source code. It supports programming languages such as C, C++, Python, and Java.

It extracts information from specially formatted comments and generates reference manuals in formats such as HTML, LaTeX, and PDF.

## 2. Key Features

- Extracts documentation from source code.
- Documents functions, classes, and modules.
- Generates cross-references and call graphs.
- Supports inheritance diagrams.
- Supports Markdown, LaTeX formulas, and code examples.
- Integrates with CI/CD workflows.

## 3. Installation

Doxygen can be installed on different operating systems.

- **Windows:** Download from the [official website](https://www.doxygen.nl/download.html).
- **macOS:** `brew install doxygen`
- **Linux:** `sudo apt-get install doxygen`

To check the installed version:

```bash
doxygen --version
```

## 4. Basic Doxygen Workflow

1. Write specially formatted comments in the source code.
2. Generate a configuration file using `doxygen -g Doxyfile`.
3. Edit the configuration file according to requirements.
4. Run `doxygen Doxyfile`.
5. View the generated documentation in HTML or LaTeX/PDF format.

## 5. Doxygen Comment Syntax

Doxygen uses special comments to describe source code.

### C/C++ Example

```cpp
/**
 * @brief Adds two numbers.
 * @param x First number.
 * @return Sum of the numbers.
 */
int add(int x);
```

### Python Example

```python
def foo(bar):
    """
    Brief description.

    :param bar: Input parameter
    :type bar: int
    :return: Computed value
    :rtype: int
    """
    return bar + 1
```

## 6. Common Doxygen Tags

| Tag | Purpose |
|---|---|
| `\brief` | Short description |
| `\param` | Parameter description |
| `\return` | Return value description |
| `\author` | Author information |
| `\version` | Version information |
| `\see` | Reference to related items |
| `\note` | Additional information |

## 7. Documenting Classes

Doxygen can document classes, their members, and their functions using special comments.

```cpp
/**
 * @class Car
 * @brief Represents a car object.
 */
class Car {
public:
    /**
     * @brief Starts the engine.
     * @return True if successful.
     */
    bool startEngine();
};
```

## 8. Grouping and Diagrams

Doxygen provides features to organize documentation and represent code relationships visually.

- Logical grouping of related documentation.
- Call graphs and include dependency diagrams.
- Graphviz integration using `HAVE_DOT = YES`.
- Diagrams using `@dot` and PlantUML directives.
- Markdown and HTML tables and images.

## 9. Doxygen Output Formats

Doxygen supports multiple documentation formats:

- **HTML:** For browsing documentation in a web browser.
- **LaTeX/PDF:** For printable reference manuals.
- **RTF:** Rich Text Format.
- **XML:** Structured documentation data.
- **DocBook:** Documentation publishing format.
- **Man Pages:** Unix manual pages.

Output formats can be enabled or disabled through the Doxyfile.

## 10. Best Practices

- Clearly describe the purpose of functions.
- Keep brief and detailed descriptions separate.
- Document all public APIs and modules.
- Use consistent documentation tags.
- Update documentation whenever source code changes.
- Generate documentation as part of continuous integration.

## 11. Doxygen with Version Control

- Store the `Doxyfile` in the source code repository.
- Update documentation along with code changes.
- Review documentation during code reviews.
- Publish generated documentation using GitHub Pages or an internal wiki.

## 12. Practical Exercise

The class PPT includes a Doxygen mini-project involving:

1. Downloading and installing Doxygen.
2. Adding Doxygen comments to a small C++ or Python codebase.
3. Generating HTML documentation.
4. Opening `html/index.html` in a browser.
5. Exploring diagrams and cross-references.

## 13. Learning Outcomes

Through this topic, I learned to:

- Understand the importance of technical documentation.
- Generate documentation from source code.
- Use Doxygen tags and comment syntax.
- Document functions and classes.
- Configure Doxygen using a Doxyfile.
- Generate HTML and LaTeX documentation.
- Create diagrams and cross-references.
- Maintain documentation using version control.

## 14. Conclusion

Doxygen simplifies software documentation by automatically generating reference manuals from source code comments. It helps improve code readability, maintenance, and collaboration in software development projects.

