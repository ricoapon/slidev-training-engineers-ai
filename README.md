## Did The Engineer Learn It Or Did AI? Training Engineers in the Age of AI

AI has fundamentally changed how engineers learn. Previous generations leaned on books, colleagues, Stack Overflow and
courses. Today's engineers have an assistant that generates explanations, designs and working code in an instant, but
it breaks something we used to rely on: a pull request no longer proves the engineer understands it. That matters,
because I believe understanding is what turns someone into a better engineer. And the research is clear on
how AI affects it: engineers who use it as an answer machine ("fix it, make no mistakes") end up worse than using no AI
at all, while those who use it as a mentor ("help me understand how this works") actually get better. With a
background in education and coaching, I'll show what understanding really means, how AI helps or hurts it, and
one concrete thing to do on your next review: ask for the chat history.

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
