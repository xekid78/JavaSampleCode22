# JavaScope
スコープの理解

## 処理
変数の有効範囲を理解するため、それぞれに変数aを定義して確認する。

## コード
```
public class sample22 {

	public static void main(String[] args) {
		int a = 10;
		int b = 20;
		int gokei = sum(a, b);
		System.out.println("変数aは" + a + "です。");
		System.out.println("変数bは" + b + "です。");
		System.out.println("合計は" + gokei + "です。");

	}

	public static int sum(int x, int y) {
		int a = 5;
		System.out.println("変数aは" + a + "です。");
		return x + y;

	}

}
```

## 出力結果  
```
変数aは5です。
変数aは10です。
変数bは20です。
合計は30です。
```

## 開発環境
| 開発ツール |  |
|:-|:-|
| 統合開発環境(IDE) | Eclipse 4.7.0 Oxygen |
| 開発言語 | Java8 |
