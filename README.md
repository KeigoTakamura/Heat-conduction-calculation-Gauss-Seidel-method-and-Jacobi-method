# Heat-conduction-calculation-Gauss-Seidel-method-and-Jacobi-method

The steady state heat conduction calculation was given by the Laplace equation, and the Jacobi method and the Gauss Seidel method were implemented in C language

C言語で書かれたた定常熱拡散問題のラプラス方程式を解いたコードです

netudendou.1.cがガウスザイデル法
netudendou.2.cがヤコビ法で実装されています
gcc -lm netudendou.1.cでコンパイルえきますがこれだと時間がかかる為gcc -lm -O3 netudendou.1.c でコンパイルすることを推奨

netudendou.2.cはOpenMPを使うことを前提にしてるためgcc -fopenmp -lm -O3 netudendou.2.cでコンパイルしてください
