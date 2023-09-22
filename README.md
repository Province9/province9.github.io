# Phi Mu Alpha Province 9 Website

## Development
1. Create a virtual environment
    ```
    python -m venv venv
    ```
2. Activate virtual environment
    ```
    source venv/bin/activate
    ```
3. Pip install mkdocs material (This will only get you so far, since we use mkdocs-material-insiders. If you're doing major changes reach out to Mason for a 
GitHub token)
    ```
    pip install mkdocs-material
    ```
4. Run dev server
    ```
    mkdocs serve
    ```

## Adding Announcement Banners
1. Add the following lines and update the text to `overrides/main.html`
```html
{% block announce %}
    <p>Donate to <a href="https://1898forward.org">1898 Forward</a> today!</p>
{% endblock %}
```
