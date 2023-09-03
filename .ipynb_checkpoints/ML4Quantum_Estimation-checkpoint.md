- Neural-network quantum state tomography for many-body systems \
https://arxiv.org/abs/1703.05334 \
Abstract \
複雑化する人工量子系の実験的実現には、量子リソースを検証し、十分に活用するための一般的な理論手法の開発が必要である。量子状態トモグラフィ(QST)は、簡単な測定から完全な量子状態を再構成することを目的としており、信頼性の高い分析を得るための重要なツールとなります。しかし、QSTに対するブルートフォースアプローチは、構成要素の数に応じて指数関数的に増大するリソースを必要とするため、小規模なシステム以外では実現不可能である。ここでは、機械学習技術を、1次元でも2次元でも、高度に絡み合った状態のQSTに効率的に利用できることを示す。驚くべきことに、その結果得られたアプローチにより、単純で実験的に利用可能な測定値から、エンタングルメント・エントロピーのような、従来困難とされてきた多体量を再構成することができる。このアプローチは、量子コンピューターから超低温原子量子シミュレーターに至るまで、既存および将来の世代のデバイスに有益である。

- Latent Space Purification via Neural Density Operators \
https://arxiv.org/abs/1801.09684 \
Abstract \
機械学習は、近い将来の量子デバイスを設計、検証、さらにはハイブリッド化する可能性について、活発に研究されている。中心的な疑問は、ニューラルネットワークが量子状態を扱いやすく表現できるかどうかである。確率的ニューラルネットワークは、生成モデリングや状態トモグラフィなど、多くの教師なしタスクに利用できる。しかし、実際の実験に応用するためには、混合量子状態を表現できなければならない。ここでは、隠れユニットの潜在空間に埋め込まれた補助自由度によって混合状態を精製することができる、制限付きボルツマンマシンに基づく密度行列をパラメトリック化する。このアルゴリズムを数値的に実装し、いくつかの典型的なもつれ光子状態に対してトモグラフィーを行うことで、標準的な手法に匹敵する忠実度を達成した。

- Liouville Space Neural Network Representation of Density Matrices \
https://arxiv.org/abs/2305.13992 \
Abstract \
アサッツ波動関数としてのニューラルネットワーク量子状態は、スピンモデルの基底状態を見つけるために多くの可能性を示してきた。最近では、この考え方を混合状態に拡張し、開放系のダイナミクスをシミュレーションすることに焦点が当てられています。これまでのほとんどのアプローチでは、システムのヒルベルト空間のコピーが追加され、それをトレースすると正しい密度行列が得られるという精製アサッツが使われてきました。ここではその代わりに、密度行列をリュービル空間で直接表現する制限付きボルツマンマシンの拡張を紹介する。これにより、平均場理論に現れる状態をコンパクトに表現することができる。散逸横場イジング模型の2つの異なるバージョンで我々のアプローチのベンチマークを行い、我々のansatzが他の最先端のアプローチと競争できることを示す。

- Mean-field theories are simple for neural quantum states \
https://arxiv.org/abs/2308.10934 \
Abstract \
量子多体波動関数を表現するための人工ニューラルネットワークの利用は、最近、基底状態と非平衡ダイナミクスの両方で大きな進歩を遂げ、大きな注目を集めている。しかし、このニューラル量子状態の枠組みで状態の複雑さを定量化することは、依然として困難である。本研究では、この重要な未解決の問題に、相補的な観点から取り組む： どの状態がNQSを用いて表現しやすいのか？具体的には、並べ替え対称性を持つ平均場理論の基底状態は、限られた数の独立したニューラルネットワークパラメータしか必要としないことを一般的なレベルで示す。熱力学的極限において、完全連結横場イジング模型（TFIM）の基底状態への収束は、たった一つのパラメータで達成できることを解析的に証明する。我々の解析を発展させ、順列対称性の破れによる1パラメータアサッツの振る舞いを探る。そのために、相互作用指数$\alpha$で特徴づけられる、調整可能な長距離相互作用を持つTFIMを考える。神経量子状態に対する1パラメーターのアサッツが、$0 \le　\alpha　\le　1$の全範囲において基底状態を正確に捉えていることを解析的に示し、この領域におけるモデルの平均場記述を示唆する。

- Quantum State Tomography using Quantum Machine Learning \
https://arxiv.org/abs/2308.10327 \
Abstract \
量子状態トモグラフィ(QST)は、未知の量子状態を再構成するための量子情報処理(QIP)の基本技術である。しかし、従来の量子状態トモグラフィ法は、必要な測定回数に制限があり、大規模な量子システムには実用的ではない。この課題を克服するために、我々は量子機械学習（QML）技術を統合し、QSTの効率を向上させることを提案する。本論文では、古典的手法と量子的手法の両方を包含するQSTのための様々なアプローチについて包括的な調査を実施する。また、QSTのための様々なQMLアプローチを実装し、多量子ビットネットワークを含む様々なシミュレーションおよび実験量子システムでその有効性を実証する。その結果、我々のQMLに基づくQSTアプローチは、従来の方法よりも大幅に少ない測定回数で高い忠実度（98%）を達成できることが示され、実用的なQIPアプリケーションのための有望なツールとなった。

- Predictive Modelling of Quantum Process with Neural Networks \
https://arxiv.org/abs/2308.08815 \
Abstract \
未知の量子過程の完全な特徴付けは、過程のトモグラフィーや、連続時間過程のハミルトニアン学習によって達成することができる。しかし、このような特徴付けは高次元の量子系では実現不可能である。本論文では、与えられた入力状態のアンサンブルに対して、未知の量子過程の振る舞いを予測する初めてのニューラルネットワークアルゴリズムを開発する。ネットワークは、数組の入出力量子状態の測定から得られた古典的データで学習される。学習後は、状態アンサンブル内の任意の入力に対応する出力状態に対して行われる、注目すべき測定セットの測定統計量を予測するために使用することができる。このモデルは、量子ゲートや量子回路の学習だけでなく、ノイズの多い量子進化を学習し、時間発展する量子状態の測定統計量を予測するタスクにも適用できる。本論文では、量子コンピュータ、量子多体物理学、量子光学における様々な関連過程について、ニューラルネットワークモデルを用いた数値計算結果を示す。

- Learning to predict arbitrary quantum processes \
https://arxiv.org/abs/2210.14894 \
Abstract \
We present an efficient machine learning (ML) algorithm for predicting any unknown quantum process  over n qubits. For a wide range of distributions  on arbitrary n-qubit states, we show that this ML algorithm can learn to predict any local property of the output from the unknown process~, with a small average error over input states drawn from . The ML algorithm is computationally efficient even when the unknown process is a quantum circuit with exponentially many gates. Our algorithm combines efficient procedures for learning properties of an unknown state and for learning a low-degree approximation to an unknown observable. The analysis hinges on proving new norm inequalities, including a quantum analogue of the classical Bohnenblust-Hille inequality, which we derive by giving an improved algorithm for optimizing local Hamiltonians. Numerical experiments on predicting quantum dynamics with evolution time up to 106 and system size up to 50 qubits corroborate our proof. Overall, our results highlight the potential for ML models to predict the output of complex quantum dynamics much faster than the time needed to run the process itself.