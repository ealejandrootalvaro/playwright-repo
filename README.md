1. npm install
2. npx playwright test
3. Validate that although the tests failed (no screenshot exists to compare) the new screenshot is generated in tests/example.spec.ts-snapshots/main-page-darwin.png since the default value for updateSnapshot is missing tests/example.spec.ts-snapshots/main-page-darwin.png