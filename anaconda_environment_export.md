# Anaconda Environment

> 환경을 파일로 내보내기 & 파일에 따라 환경 설치하기

<br/>

- export environment to a file

```bash
conda env export -n base > env.yml
```

<br/>

<br/>

- install environment according to a file

```bash
conda env create -n mytorch python=3.8.8 -f env.yml
```

