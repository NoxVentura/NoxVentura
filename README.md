<div align=center>

# Hello, World! 👋

</div>

<p style=text-align:justify> Hi, I'm Nox, 18 years old and currently residing in Singapore. I'm (quite) fluent in JavaScript and Python. I had a brief taste in C# and Java, though I've never programmed anything else with them. I'm the creator of the SagaScript programming language. </p>

<p style=text-align:justify> I enjoy reading e-books (sometimes fan-fiction) and writing my own stories, mainly science fantasy and dystopia. I am also fond of learning about new programming languages, many of which I adopted in mine (see below). <p>

<p style=text-align:justify> This year happens fast. I'm on my third year of polytechnic college. I've just (re)opened this account on 18/9 after a long hiatus, and I'm going into the last semester of my diploma (this year is ending fast)! </p>

![Noel's GitHub stats](https://github-readme-stats.vercel.app/api?username=nxltm&theme=tokyonight)

<div align=center>

## Favorites

</div>

- Pronouns: He/Him
- Religion: Christian
- Fun fact: I play drums.
- Favorite games, lore-wise: 
  - League of Legends 
  - Warframe
  - Final Fantasy
  - Anthem 
  - Destiny
  - Halo 
  - Doom
- Favorite anime:
  - One Punch Man

<div align=center>

## Theme

[![](https://github-readme-stats.vercel.app/api/pin/?username=nxltm&repo=inizio-theme)](https://github.com/nxltm/inizio-theme)

</div>

<div align=center>

## My Work

Check out my new programming language, **SagaScript**. 

[![SagaScript](https://github-readme-stats.vercel.app/api/pin/?username=nxltm&repo=sagascript)](https://github.com/nxltm/sagascript)

<p style=text-align:justify> SagaScript is a <i> principled </i> programming language intended to be a drop-in replacement for JavaScript, and compiles to it. It will offer new and powerful features, and a comprehensive standard library, providing everything you need to develop modern apps quicker and safer. </p>

<p style=text-align:justify> SagaScript is heavily influenced by other modern languages, either through syntax or the standard library (in descending influence): </p>

```txt
Nim, Python, Swift, Scala, Go, Rust, TypeScript, Elixir, F#, OCaml, CoffeeScript, Haskell, Flix, C#, Kotlin, LiveScript, Bash, Smalltalk, YAML, Elm, Ada, Erlang, PureScript, Java. 
```

<p style=text-align:justify> <b> I'll be willing to collaborate </b> with someone to expand my ideas and help me complete the documentation. I've been working on the grammar from scratch for a month and a half now. </p>

</div>

```coffee
#: Generates a custom Fibonacci sequence
#: with an arbitrary set of integers
rec gen def fib[N: int](*start: []N, term: N): N =
  if term of start:
    yield start[term - 1]
  elif term > len start:
    yield from in term - len start to term
      select x => fib start, x
      fold left (+)
  else:
    raise new Error
      "Invalid term in Fibonacci sequence"
```

(compiled result in TypeScript)

```ts
import S from "@Saga/core";
import {len, range} from "@Saga/std";
import {Int} from "@Saga/types";

export default function* fib<N extends Int>(...start: N[], term: N): N {
  if (term in start) {
    yield start[term - 1];
  } else if (term > len(start)) {
    yield (range(term - len(start)).to(term) as S.Range)
      .select(x => fib(start, x))
      .foldLeft(($0, $1) => $0 + $1);
  } else {
    throw new Error("Invalid term in Fibonacci sequence");
  }
};
```

<!---
nxltm/nxltm is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<div align=center>

## Contact Me / AMA

Instagram | Reddit | Twitter (soon)

</div>