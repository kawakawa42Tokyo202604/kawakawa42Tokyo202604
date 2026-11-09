<p align="center">
  <img src="assets/profile-header.svg" alt="kawakawa | 42 Tokyo · Systems Programming · Infrastructure" width="100%" />
</p>

## 🟢 About

I build C, Python, and Go programs through 42 Tokyo projects, including libraries, route planners, a multiplayer game, LLM function calling, and containerized web infrastructure.

42 Tokyoのプロジェクトを通じて、C・Python・Goのライブラリ、経路探索、ネットワークゲーム、LLMによる関数呼び出しデータの生成、Dockerを使ったWeb環境の構築に取り組んでいます。

- **Name** — kawakawa
- **Learning** — C / Python / Go / Assembly / Systems programming / Infrastructure
- **Focus** — メモリ管理、並行処理、経路探索、TCP通信、LLMの構造化出力、コンテナによるサービスの分離。
- **Code** — 学習課題と実装を [42Tokyocursus](https://github.com/kawakawa42Tokyo202604/42Tokyocursus) にまとめています。

## 🟢 Tech Stack

<table align="center">
  <tr>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=c&theme=dark" alt="C" /><br />C</td>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=python&theme=dark" alt="Python" /><br />Python</td>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=go&theme=dark" alt="Go" /><br />Go</td>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=bash&theme=dark" alt="Shell" /><br />Shell</td>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=linux&theme=dark" alt="Linux" /><br />Linux</td>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=docker&theme=dark" alt="Docker" /><br />Docker</td>
  </tr>
</table>

<table align="center">
  <tr>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=git&theme=dark" alt="Git" /><br />Git</td>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=github&theme=dark" alt="GitHub" /><br />GitHub</td>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=vim&theme=dark" alt="Vim" /><br />Vim</td>
    <td align="center" width="88"><img height="56" width="56" src="https://skillicons.dev/icons?i=vscode&theme=dark" alt="VS Code" /><br />VS Code</td>
    <td align="center" width="88"><img height="56" width="56" src="assets/k3s.svg" alt="K3s" /><br />K3s</td>
  </tr>
</table>

| Category | Technologies |
| --- | --- |
| Languages | C / Python / Go / Shell / x86-64 Assembly |
| Systems | Linux / POSIX Threads / ファイルディスクリプタ / メモリ管理 |
| Infrastructure | Docker / Docker Compose / K3s / NGINX / WordPress / PHP-FPM / MariaDB / Redis |
| Development | Git / Make / Vim / VS Code / mypy / flake8 |

## 🟢 Featured projects

- **[The Answer Protocol](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/TAP)** — Go / TCP / Fyne<br>
  A shared text-adventure world with a TCP server, terminal and graphical clients, combat, quests, and chat.<br>
  ギリシャ神話の世界を複数人で探索するゲーム。Go製のTCPサーバーとCLI・GUIクライアントを実装し、戦闘・クエスト・チャット・状態の保存を扱います。
- **[Fly-in](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/FLYIN)** — Python / Pathfinding<br>
  Plan drone movements while respecting location capacities, connection capacities, and travel times.<br>
  複数のドローンを目的地まで運ぶ経路と順番を計算するシミュレーター。各地点・経路の台数制限、通行禁止区域、移動時間を考慮します。
- **[Call Me Maybe](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/callmemaybe)** — Python / LLM / JSON<br>
  Convert written requests into function names and arguments using a small language model and constrained decoding.<br>
  文章の指示から、呼び出す関数名と引数をJSONで生成するツール。小型言語モデルの出力候補を制御し、自作のトークン分割と入力検証を組み合わせています。
- **[Codexion](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/codexion)** — C / POSIX Threads<br>
  Simulate developers sharing equipment, with waiting queues and deadlines for their work.<br>
  複数の開発者が共有機器を順番に使うシミュレーション。スレッド間の同期、要求順・期限順の待ち行列、期限切れの監視を扱います。
- **[Inception](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/Inception)** — Docker / Docker Compose / Shell<br>
  A WordPress hosting environment with HTTPS, persistent data, backups, and restoration checks.<br>
  記事を投稿・閲覧できるWordPressサイトの実行環境。NGINX・WordPress・MariaDBを個別のコンテナで動かし、HTTPS・データの永続化・バックアップと復元検証を組み合わせています。
- **[push_swap](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/push_swap)** — C / Sorting algorithms<br>
  Generate a short sequence of stack operations to sort integers, then validate it with a checker.<br>
  整数を小さい順に並べるための交換・移動・回転の手順を出力するプログラム。入力に応じた戦略の選択、操作数の計測、検証用checkerを備えています。

<details open>
<summary>42 Tokyo project list / 課題一覧</summary>

| Project | Language / Technology | About |
| --- | --- | --- |
| [Piscine](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/piscine) | C / Shell | Cの基本文法、文字列・配列操作、Shell、Rush、BSQに取り組む課題群。 |
| [libft](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/libft) | C | 標準Cライブラリの基本関数、文字列ユーティリティ、連結リスト操作をまとめた自作ライブラリ。 |
| [ft_printf](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/ft_printf) | C | 書式指定文字列を解析し、文字列・数値・ポインタなどを出力する`printf`の一部を再実装。 |
| [get_next_line](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/get_next_line) | C | ファイルディスクリプタから1行ずつ読み取る関数。ボーナスでは複数の読み取り対象の状態を管理。 |
| [push_swap](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/push_swap) | C | スタック操作によるソート、複数戦略の選択、命令数の計測、`checker`による結果確認。 |
| [Python modules 00–10](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/PythonModule) | Python | 基本文法、オブジェクト指向、例外処理、ファイル入出力、パッケージ、Pydantic、デコレータを学ぶ課題群。 |
| [A-Maze-ing](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/A-maze-ing) | Python | 設定ファイルから迷路を生成し、入口から出口への経路を探索・出力するプログラム。 |
| [A-Maze-ing bonus](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/A-maze-ing-bonus) | Python | DFS / Kruskalの生成アルゴリズム切り替え、対話式の表示操作、再利用可能なパッケージ化。 |
| [Codexion](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/codexion) | C / POSIX Threads | 共有リソースの同期、FIFO / EDFの待ち行列、期限の監視を組み合わせた並行処理シミュレーション。 |
| [Inception](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/Inception) | Docker / Shell | 自作コンテナによるWebインフラと、TLS・永続化・キャッシュ・バックアップ・復元検証。 |
| [The Answer Protocol](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/TAP) | Go / TCP / Fyne | 複数人で探索・会話・戦闘を楽しむゲーム。サーバーとCLI・GUIクライアントを実装。 |
| [Call Me Maybe](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/callmemaybe) | Python / LLM | 文章の指示を、関数名と引数を持つJSONデータへ変換。 |
| [Fly-in](https://github.com/kawakawa42Tokyo202604/42Tokyocursus/tree/main/FLYIN) | Python / Pathfinding | 地点・経路の容量と移動時間を考慮し、複数ドローンの移動を計画。 |
| [Dr Quine](https://github.com/kawakawa42Tokyo202604/Dr_Quine) | C / Assembly / Go | 自分のソースを表示・保存・連鎖生成する自己複製プログラム。 |
| [libasm](https://github.com/kawakawa42Tokyo202604/libasm) | x86-64 Assembly | Cから呼び出せる文字列・メモリ・ファイル入出力の基本関数集。 |
| [Inception of Things](https://github.com/kawakawa42Tokyo202604/Inception-of-Things) | Vagrant / K3s | 開発中。p1のサーバー・ワーカー構成と、p2のサーバー作成までを実装。 |
| [B](https://github.com/kawakawa42Tokyo202604/B) | C / Compiler | 開発準備段階。B言語コンパイラの構成とMakefileを用意し、本体は未実装。 |

</details>

## 🟢 GitHub Stats

<p align="center">
  <a href="https://github.com/kawakawa42Tokyo202604">
    <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kawakawa42Tokyo202604&theme=github_dark&name=kawakawa&bg_color=0D1117&title_color=79D99A&text_color=C9F7D2&border_color=245333&icon_color=79D99A&chart_color=5FA876" alt="GitHub contributions over the last year" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/kawakawa42Tokyo202604">
    <img height="180" src="assets/github-stats.svg" alt="kawakawa's GitHub stats" />
  </a>
  <a href="https://github.com/kawakawa42Tokyo202604">
    <img height="180" src="assets/top-langs.svg" alt="Most used languages for kawakawa42Tokyo202604" />
  </a>
</p>

<p align="center">
  <img height="180" src="https://streak-stats.demolab.com?user=kawakawa42Tokyo202604&theme=dark&hide_border=true&background=0D1117&ring=39FF14&fire=39FF14&currStreakLabel=39FF14&currStreakNum=C9F7D2&sideLabels=C9F7D2&sideNums=C9F7D2&dates=718A76" alt="kawakawa's GitHub contribution streak" />
</p>
