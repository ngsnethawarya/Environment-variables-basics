Hardcoding passwords or API keys directly into code creates unnecessary risk.

Environment variables provide a safer way to store configuration values outside the application.

Benefits include:

Easier configuration changes.
Reduced risk of exposing secrets.
Better separation between code and configuration.
Simpler deployment across different environments.

Even small projects benefit from developing this habit early


api_key = os.getenv("API_KEY")

if api_key:
    print("API key loaded.")
else:
    print("API key not found.")
