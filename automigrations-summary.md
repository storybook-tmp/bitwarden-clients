# Automigrations summary

These files could not be migrated automatically.
Update them by hand.
A section disappears once its migration runs again without failures.
Delete this file when you are done.

## story-sort-to-main

| File | Reason |
| ---- | ------ |
| `.storybook/main.ts` | Cannot automigrate storySort: Cannot mutate parameters.options.storySort because the target contains dynamic key. Storybook no longer reads parameters.options.storySort from the preview. Move it to storySorts in the main config manually and remove the preview property. |
