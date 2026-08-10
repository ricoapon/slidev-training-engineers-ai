## Did They Learn It Or Did AI? Guiding Engineers in the Age of AI

AI has fundamentally changed how engineers learn. Previous generations leaned on books, colleagues, Stack Overflow and
courses. Today's engineers have an assistant that generates explanations, designs and working code in an instant. But it
breaks something we used to rely on: a pull request no longer means the engineer understands it. How do you give
feedback on work that's AI-generated? How do you encourage AI without letting it replace learning? In this talk I'll
make the case for reviewing not just the code, but how the engineer used AI to produce it. I'll show the difference
between using AI as an answer machine ("fix it, make no mistakes") and as a mentor ("help me understand how this
works"). The research is clear: using it as an answer machine makes engineers worse than using no AI at all. You'll
leave with a new way to look at your engineers' work and practical ideas for helping them use AI to learn.

## Info

This is the slide deck, made using [Slidev](https://sli.dev/), for my presentation that takes about 15 minutes.

## Present

Either go to https://trainingengineersai.ricoapon.nl/ or run `npm run dev`.

## Present offline

This repository has been created with the possibility to run offline. To do so, first execute the following commands
while you have internet:

1. `npm install`
2. `npm run build`

You should now have a `dist` directory with the files for the presentation. Run this command when having no internet:

```
python -m http.server --directory dist
```

The presentation is now available at http://localhost:8000.
