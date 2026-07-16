<div align="center">

<samp>LAOLVFAN / BACKEND × AI RELIABILITY</samp>

# Build systems. Break assumptions.

**Nanjing University undergraduate · Java backend developer · TensorFlow/XLA bug investigator**

NJUer focused on reliable Java backend systems and correctness in AI frameworks.

</div>

```console
$ ./profile --status

identity    NJU undergraduate
building    Java / Spring backend systems
exploring   TensorFlow & XLA correctness
approach    ship the system · reproduce the edge case · verify the result
```

## Selected work

### [Git-Guild](https://github.com/ZhenchangMin/Git-Guild)

An RPG-inspired collaboration platform that turns real repository work into
quests—from publishing an issue to submitting, reviewing, and merging a pull
request.

`Architecture` · `Backend Engineering` · `Team Project`

- Worked across system architecture, authentication, quest/review workflows,
  Gitea integration, and CI-backed verification.
- Built with **Java 17**, **Spring Boot 3**, **Spring Security**, **JPA**,
  **MySQL**, **Docker Compose**, and **Vue 3**.
- Designed as a working end-to-end system rather than a static course demo.

→ [Explore the repository](https://github.com/ZhenchangMin/Git-Guild)

### [TensorFlow / XLA bug investigations](https://github.com/tensorflow/tensorflow/issues?q=is%3Aissue+author%3Alaolvfan)

I investigate observable differences between TensorFlow eager execution,
graphs, and XLA, then reduce them to reproducible bug reports.

Selected reports:

- [XLA rewrites `exp(a) * exp(b)` to `exp(a + b)`, changing `NaN` to `1.0`](https://github.com/tensorflow/tensorflow/issues/123169)
- [Heap corruption in eager `tf.matmul` with rank-4 broadcast inputs on CPU](https://github.com/tensorflow/tensorflow/issues/123109)
- [`tf.sigmoid` on `bfloat16` is non-monotonic on CPU](https://github.com/tensorflow/tensorflow/issues/123104)

→ [View all TensorFlow reports](https://github.com/tensorflow/tensorflow/issues?q=is%3Aissue+author%3Alaolvfan)

## Working set

<p>
  <img alt="Java" src="https://img.shields.io/badge/Java-111827?style=flat-square&logo=openjdk&logoColor=22d3ee">
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-111827?style=flat-square&logo=springboot&logoColor=22d3ee">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-111827?style=flat-square&logo=mysql&logoColor=22d3ee">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=22d3ee">
  <img alt="TensorFlow" src="https://img.shields.io/badge/TensorFlow-111827?style=flat-square&logo=tensorflow&logoColor=22d3ee">
</p>

```text
backend     Java · Spring Boot · Spring Security · JPA · REST APIs
data        MySQL · Redis
infra       Docker Compose · GitHub Actions · Gitea
ai systems  TensorFlow · XLA · numerical and compiler edge cases
```

## Current direction

- Building backend systems whose behavior is explicit, testable, and observable.
- Learning from real framework failures instead of treating abstractions as black boxes.
- Turning investigations into small, reproducible artifacts that other engineers can verify.

<div align="center">

<samp>READ THE CODE · REPRODUCE THE BUG · LEAVE THE SYSTEM BETTER</samp>

</div>
