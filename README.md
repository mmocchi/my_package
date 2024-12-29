# my_package

## 概要
このパッケージは、Python プロジェクトのテンプレートです。

## プロジェクト構造
```
my_package/
├── src/
│   └── my_package/
│       ├── moduleA/
│       ├── moduleB/
│       └── utils/
├── tests/
├── .vscode/
├── pyproject.toml
├── Taskfile.yml
└── README.md
```

## 必要条件
- Python 3.x
- mise


## インストール方法

### 開発環境のセットアップ
1. リポジトリのクローン:
```bash
git clone https://github.com/mmocchi/my_package.git
cd my_package
```

2. 依存関係のインストール:
```bash
mise install
```

### 開発用依存関係のインストール
```bash
uv sync
```

## 使用方法

### タスクの実行
プロジェクトには `Taskfile.yml` が含まれており、一般的なタスクを簡単に実行できます：

```bash
# テストの実行
task test

# リンターの実行
task lint

# フォーマットの実行
task format
```
