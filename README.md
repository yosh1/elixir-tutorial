# Elixir Tutorial
This is elixir tutorial repository.

---

## 開発環境

### Mac

```
$ brew update
$ brew install elixir
```

### Docker

```
$ docker run -it --rm elixir (bash)
```

---

## 実行

### シェル

```
$ iex
```

### ファイルをコンパイル

```
$ elixir <file-name>.exs
```

---

## 基本型

```
iex> 1          # integer

iex> 0x1F       # integer

iex> 1.0        # float

iex> true       # boolean

iex> :atom      # atom / symbol

iex> "elixir"   # string

iex> [1, 2, 3]  # list

iex> {1, 2, 3}  # tuple
```

### サンプル

```
iex> 40 + 2
# 42

iex> "hello" <> " world"
# "hello world"

iex> [1, 2, 3] ++ [4, 5, 6]
# [1, 2, 3, 4, 5, 6]
```

## モジュール定義

```
defmodule ModuleName do

end
```

- 名前空間みたいなもの
- モジュール名は大文字から始まるキャメルケースでなければならない
- doが必要

## 関数定義

```
def function_name(arg) do

end
```

- 関数名はスネークケース
- 関数はモジュールの中に書く
- doが必要

## IO.puts

```
IO.puts "Hello!"
#=> Hello!
```

- rubyのputに似てるらしい（知らない）
