# General notes on robust python programming
1. Annotate only what will be maintained in a future.
2. There are a lot of default types we can use (collections).
3. Create customized types (`tables: Dict[str, pl.DataFrame]`, logger: `library.observability.logger.Logger`).
4. Optimize to for predictability of code.
5. Annotate any new line of code you write, annotate any old line of code you change.
6. Annotate the core of the code base specific to business.
7. Annotate libraries and reusable components.
8. Use tools such as mypy, static typing, ruff.