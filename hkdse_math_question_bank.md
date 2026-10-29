[hkdse_html.md](https://github.com/user-attachments/files/34130826/hkdse_html.md)
[
  {
    "id": "2023_Q1",
    "year": 2023,
    "qNum": "Q1",
    "topicId": 1,
    "topicName": "公式主项变换",
    "topicNameEn": "Change of Subject",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2023 DSE A1 Q1",
    "titleZh": "公式主项变换",
    "titleEn": "Change of Subject",
    "questionZh": "化 $h$ 为公式 $\\frac{5}{h+k} = \\frac{k}{h-3}$ 的主项。",
    "questionEn": "Make $h$ the subject of the formula $\\frac{5}{h+k} = \\frac{k}{h-3}$.",
    "solutionZh": [
      { "step": "$5(h-3) = k(h+k)$", "mark": "1M", "desc": "交叉相乘消去分母" },
      { "step": "$5h - 15 = kh + k^2 \\implies 5h - kh = k^2 + 15$", "mark": "1M", "desc": "展开括号并将含 $h$ 的项集中在左侧" },
      { "step": "$h(5-k) = k^2 + 15 \\implies h = \\frac{k^2+15}{5-k}$", "mark": "1A", "desc": "提取公因式 $h$ 并求出结果" }
    ],
    "solutionEn": [
      { "step": "$5(h-3) = k(h+k)$", "mark": "1M", "desc": "Cross multiply to remove denominators" },
      { "step": "$5h - 15 = kh + k^2 \\implies 5h - kh = k^2 + 15$", "mark": "1M", "desc": "Expand and group terms containing $h$ on LHS" },
      { "step": "$h(5-k) = k^2 + 15 \\implies h = \\frac{k^2+15}{5-k}$", "mark": "1A", "desc": "Factor out $h$ and solve" }
    ],
    "pitfallsZh": "注意移项时的符号变动，$-15$ 移至右侧变为 $+15$。",
    "pitfallsEn": "Watch out for sign changes when moving terms across the equals sign.",
    "finalAnswer": "h = (k^2 + 15) / (5 - k)"
  },
  {
    "id": "2023_Q2",
    "year": 2023,
    "qNum": "Q2",
    "topicId": 2,
    "topicName": "指数律",
    "topicNameEn": "Laws of Indices",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2023 DSE A1 Q2",
    "titleZh": "指数律化简",
    "titleEn": "Laws of Indices",
    "questionZh": "化简 $\\frac{x^{-8}y}{(x^7 y^9)^{-6}}$，并以正指数表示答案。",
    "questionEn": "Simplify $\\frac{x^{-8}y}{(x^7 y^9)^{-6}}$ and express your answer with positive indices.",
    "solutionZh": [
      { "step": "分母 $= x^{-42} y^{-54}$", "mark": "1M", "desc": "展开分母括号次方" },
      { "step": "原式 $= x^{-8 - (-42)} y^{1 - (-54)}$", "mark": "1M", "desc": "同底数相除，指数相减" },
      { "step": "$= x^{34} y^{55}$", "mark": "1A", "desc": "计算最终正指数结果" }
    ],
    "solutionEn": [
      { "step": "Denominator $= x^{-42} y^{-54}$", "mark": "1M", "desc": "Expand denominator power" },
      { "step": "Expression $= x^{-8 - (-42)} y^{1 - (-54)}$", "mark": "1M", "desc": "Subtract indices for division" },
      { "step": "$= x^{34} y^{55}$", "mark": "1A", "desc": "Simplify to positive indices" }
    ],
    "pitfallsZh": "注意负负得正：$-8 - (-42) = 34$；且 $y$ 的隐式指数为 1。",
    "pitfallsEn": "Beware of double negatives: $-8 - (-42) = 34$; $y$ has an implicit power of 1.",
    "finalAnswer": "x^34 * y^55"
  },
  {
    "id": "2022_Q1",
    "year": 2022,
    "qNum": "Q1",
    "topicId": 2,
    "topicName": "指数律",
    "topicNameEn": "Laws of Indices",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2022 DSE A1 Q1",
    "titleZh": "指数律化简",
    "titleEn": "Laws of Indices",
    "questionZh": "化简 $\\frac{(a^3 b^{-2})^4}{a^{-5} b^6}$，并以正指数表示答案。",
    "questionEn": "Simplify $\\frac{(a^3 b^{-2})^4}{a^{-5} b^6}$ and express your answer with positive indices.",
    "solutionZh": [
      { "step": "分子 $= a^{12} b^{-8}$", "mark": "1M", "desc": "展开分子括号" },
      { "step": "原式 $= a^{12 - (-5)} b^{-8 - 6} = a^{17} b^{-14}$", "mark": "1M", "desc": "同底数指数相减" },
      { "step": "$= \\frac{a^{17}}{b^{14}}$", "mark": "1A", "desc": "转化为正指数分式" }
    ],
    "solutionEn": [
      { "step": "Numerator $= a^{12} b^{-8}$", "mark": "1M", "desc": "Expand numerator power" },
      { "step": "Expression $= a^{12 - (-5)} b^{-8 - 6} = a^{17} b^{-14}$", "mark": "1M", "desc": "Subtract exponents" },
      { "step": "$= \\frac{a^{17}}{b^{14}}$", "mark": "1A", "desc": "Express in positive index form" }
    ],
    "pitfallsZh": "题目要求“以正指数表示”，答案不可保留 $b^{-14}$。",
    "pitfallsEn": "Answer must be expressed in positive index form; do not leave negative powers.",
    "finalAnswer": "a^17 / b^14"
  },
  {
    "id": "2022_Q2",
    "year": 2022,
    "qNum": "Q2",
    "topicId": 4,
    "topicName": "方程与应用题",
    "topicNameEn": "Equations & Applications",
    "difficulty": "Medium",
    "marks": 4,
    "yearRef": "2022 DSE A1 Q2",
    "titleZh": "二元一次方程应用题",
    "titleEn": "Simultaneous Linear Equations",
    "questionZh": "成人的入场费为 $\$70$，小童的入场费为 $\$30$。现卖出 120 张门票，总收入为 $\$5600$。求卖出成人门票的数目。",
    "questionEn": "The ticket price for an adult is $\$70$ and for a child is $\$30$. A total of 120 tickets are sold for $\$5600$. Find the number of adult tickets sold.",
    "solutionZh": [
      { "step": "设卖出成人门票 $x$ 张，小童门票 $y$ 张。联立方程：\\n$x + y = 120$ \\n$70x + 30y = 5600$", "mark": "1M", "desc": "正确建立二元一次方程组" },
      { "step": "$70x + 30(120 - x) = 5600$", "mark": "1M", "desc": "消元法代入求解" },
      { "step": "$40x = 2000 \\implies x = 50$", "mark": "1A", "desc": "解出 $x$ 的值" },
      { "step": "答：卖出成人门票的数目为 50 张。", "mark": "1A", "desc": "完整作答" }
    ],
    "solutionEn": [
      { "step": "Let $x$ be adult tickets and $y$ be child tickets:\\n$x + y = 120$\\n$70x + 30y = 5600$", "mark": "1M", "desc": "Set up linear equations" },
      { "step": "$70x + 30(120 - x) = 5600$", "mark": "1M", "desc": "Substitute to solve" },
      { "step": "$40x = 2000 \\implies x = 50$", "mark": "1A", "desc": "Solve for $x$" },
      { "step": "The number of adult tickets sold is 50.", "mark": "1A", "desc": "Final answer statement" }
    ],
    "pitfallsZh": "注意分清成人和小童的价格，避免 $70$ 和 $30$ 的系数倒置。",
    "pitfallsEn": "Take care not to swap the prices for adult and child tickets.",
    "finalAnswer": "50"
  },
  {
    "id": "2021_Q1",
    "year": 2021,
    "qNum": "Q1",
    "topicId": 2,
    "topicName": "指数律",
    "topicNameEn": "Laws of Indices",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2021 DSE A1 Q1",
    "titleZh": "指数律化简",
    "titleEn": "Laws of Indices",
    "questionZh": "化简 $(a b^3)(a^{-2} b^4)^5$，并以正指数表示答案。",
    "questionEn": "Simplify $(a b^3)(a^{-2} b^4)^5$ and express your answer with positive indices.",
    "solutionZh": [
      { "step": "$(a^{-2} b^4)^5 = a^{-10} b^{20}$", "mark": "1M", "desc": "展开括号次方" },
      { "step": "原式 $= a^{1 + (-10)} b^{3 + 20} = a^{-9} b^{23}$", "mark": "1M", "desc": "同底数相乘，指数相加" },
      { "step": "$= \\frac{b^{23}}{a^9}$", "mark": "1A", "desc": "化为正指数表示" }
    ],
    "solutionEn": [
      { "step": "$(a^{-2} b^4)^5 = a^{-10} b^{20}$", "mark": "1M", "desc": "Expand bracket power" },
      { "step": "Expression $= a^{1 + (-10)} b^{3 + 20} = a^{-9} b^{23}$", "mark": "1M", "desc": "Add indices for multiplication" },
      { "step": "$= \\frac{b^{23}}{a^9}$", "mark": "1A", "desc": "Express with positive index" }
    ],
    "pitfallsZh": "注意第一个 $a$ 的指数是 1 而不是 0。",
    "pitfallsEn": "The index of the first $a$ is 1, not 0.",
    "finalAnswer": "b^23 / a^9"
  },
  {
    "id": "2021_Q2",
    "year": 2021,
    "qNum": "Q2",
    "topicId": 5,
    "topicName": "不等式",
    "topicNameEn": "Linear Inequalities",
    "difficulty": "Medium",
    "marks": 4,
    "yearRef": "2021 DSE A1 Q2",
    "titleZh": "一元一次不等式",
    "titleEn": "Linear Inequalities",
    "questionZh": "(a) 解不等式 $\\frac{3x - 2}{5} > 2x + 1$。\\n(b) 求满足 (a) 的不等式的最大整数。",
    "questionEn": "(a) Solve the inequality $\\frac{3x - 2}{5} > 2x + 1$.\\n(b) Find the maximum integer satisfying the inequality in (a).",
    "solutionZh": [
      { "step": "$3x - 2 > 10x + 5$", "mark": "1M", "desc": "两边同乘以 5 消去分母" },
      { "step": "$-7x > 7 \\implies x < -1$", "mark": "1A", "desc": "同除以负数 $-7$，不等号变向" },
      { "step": "小于 $-1$ 的最大整数为 $-2$。", "mark": "1A", "desc": "求出符合条件的最大整数" }
    ],
    "solutionEn": [
      { "step": "$3x - 2 > 10x + 5$", "mark": "1M", "desc": "Multiply both sides by 5" },
      { "step": "$-7x > 7 \\implies x < -1$", "mark": "1A", "desc": "Divide by $-7$ and reverse inequality sign" },
      { "step": "The maximum integer strictly less than $-1$ is $-2$.", "mark": "1A", "desc": "Identify maximum integer" }
    ],
    "pitfallsZh": "除以负数时忘记倒转不等号（由 $>$ 变 $<$）；$-1$ 本身不符合条件（因必须严格小于）。",
    "pitfallsEn": "Forget to flip inequality sign when dividing by negative number; $-1$ is excluded as inequality is strict.",
    "finalAnswer": "x < -1 ; Maximum Integer = -2"
  },
  {
    "id": "2020_Q1",
    "year": 2020,
    "qNum": "Q1",
    "topicId": 2,
    "topicName": "指数律",
    "topicNameEn": "Laws of Indices",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2020 DSE A1 Q1",
    "titleZh": "指数律化简",
    "titleEn": "Laws of Indices",
    "questionZh": "化简 $\\frac{(mn^{-2})^5}{m^{-4}}$，并以正指数表示答案。",
    "questionEn": "Simplify $\\frac{(mn^{-2})^5}{m^{-4}}$ and express your answer with positive indices.",
    "solutionZh": [
      { "step": "分子 $= m^5 n^{-10}$", "mark": "1M", "desc": "展开分子次方" },
      { "step": "原式 $= m^{5 - (-4)} n^{-10} = m^9 n^{-10}$", "mark": "1M", "desc": "同底数相除" },
      { "step": "$= \\frac{m^9}{n^{10}}$", "mark": "1A", "desc": "化为正指数形式" }
    ],
    "solutionEn": [
      { "step": "Numerator $= m^5 n^{-10}$", "mark": "1M", "desc": "Expand numerator power" },
      { "step": "Expression $= m^{5 - (-4)} n^{-10} = m^9 n^{-10}$", "mark": "1M", "desc": "Apply division law for base $m$" },
      { "step": "$= \\frac{m^9}{n^{10}}$", "mark": "1A", "desc": "Express with positive index" }
    ],
    "pitfallsZh": "分母的负指数移至分子时注意符号：$5 - (-4) = 9$。",
    "pitfallsEn": "Careful with double negative: $5 - (-4) = 9$.",
    "finalAnswer": "m^9 / n^10"
  },
  {
    "id": "2020_Q2",
    "year": 2020,
    "qNum": "Q2",
    "topicId": 6,
    "topicName": "余数定理与多项式",
    "topicNameEn": "Remainder Theorem & Polynomials",
    "difficulty": "Medium",
    "marks": 5,
    "yearRef": "2020 DSE A2 Q2",
    "titleZh": "多项式与余数定理",
    "titleEn": "Remainder Theorem",
    "questionZh": "设 $f(x) = 2x^3 + ax^2 + bx - 12$。当 $f(x)$ 除以 $(x - 2)$ 时，余数为 0；当 $f(x)$ 除以 $(x + 1)$ 时，余数为 $-18$。\\n(a) 求 $a$ 及 $b$ 的值。\\n(b) 解方程 $f(x) = 0$。",
    "questionEn": "Let $f(x) = 2x^3 + ax^2 + bx - 12$. When $f(x)$ is divided by $(x - 2)$, remainder is 0; when divided by $(x + 1)$, remainder is $-18$.\\n(a) Find $a$ and $b$.\\n(b) Solve $f(x) = 0$.",
    "solutionZh": [
      { "step": "$f(2) = 0 \\implies 4a + 2b = -4 \\implies 2a + b = -2$", "mark": "1M", "desc": "根据余数定理代入 $x=2$" },
      { "step": "$f(-1) = -18 \\implies a - b = -4$", "mark": "1M", "desc": "代入 $x=-1$" },
      { "step": "解得 $a = -2, b = 2$", "mark": "1A", "desc": "联立求解 $a$ 和 $b$" },
      { "step": "$f(x) = (x - 2)(2x^2 + 2x + 6) = 0$", "mark": "1M", "desc": "多项式因式分解" },
      { "step": "实数解为 $x = 2$ （二次部分无实解）。", "mark": "1A", "desc": "得出方程实解" }
    ],
    "solutionEn": [
      { "step": "$f(2) = 0 \\implies 2a + b = -2$", "mark": "1M", "desc": "Apply remainder theorem for $x=2$" },
      { "step": "$f(-1) = -18 \\implies a - b = -4$", "mark": "1M", "desc": "Apply remainder theorem for $x=-1$" },
      { "step": "$a = -2, b = 2$", "mark": "1A", "desc": "Solve linear system" },
      { "step": "$f(x) = (x - 2)(2x^2 + 2x + 6) = 0$", "mark": "1M", "desc": "Factorize polynomial" },
      { "step": "Real root $x = 2$ (quadratic part has non-real roots).", "mark": "1A", "desc": "Provide real roots" }
    ],
    "pitfallsZh": "$2x^2 + 2x + 6 = 0$ 的判别式 $\\Delta < 0$，无实根，别强行求解。",
    "pitfallsEn": "The discriminant of $2x^2 + 2x + 6 = 0$ is negative, so there are no additional real roots.",
    "finalAnswer": "a = -2, b = 2; x = 2"
  },
  {
    "id": "2019_Q1",
    "year": 2019,
    "qNum": "Q1",
    "topicId": 1,
    "topicName": "公式主项变换",
    "topicNameEn": "Change of Subject",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2019 DSE A1 Q1",
    "titleZh": "公式主项变换",
    "titleEn": "Change of Subject",
    "questionZh": "化 $h$ 为公式 $9(h+6k) = 7h+8$ 的主项。",
    "questionEn": "Make $h$ the subject of the formula $9(h+6k) = 7h+8$.",
    "solutionZh": [
      { "step": "$9h + 54k = 7h + 8$", "mark": "1M", "desc": "展开括号" },
      { "step": "$2h = 8 - 54k$", "mark": "1M", "desc": "移项集中 $h$" },
      { "step": "$h = 4 - 27k$", "mark": "1A", "desc": "两边同除以 2 得到结果" }
    ],
    "solutionEn": [
      { "step": "$9h + 54k = 7h + 8$", "mark": "1M", "desc": "Expand LHS bracket" },
      { "step": "$2h = 8 - 54k$", "mark": "1M", "desc": "Isolate $2h$" },
      { "step": "$h = 4 - 27k$", "mark": "1A", "desc": "Divide by 2 to solve for $h$" }
    ],
    "pitfallsZh": "记得分子两项都要除以 2：$8/2 = 4, 54/2 = 27$。",
    "pitfallsEn": "Make sure to divide both terms on RHS by 2.",
    "finalAnswer": "h = 4 - 27k"
  },
  {
    "id": "2018_Q1",
    "year": 2018,
    "qNum": "Q1",
    "topicId": 1,
    "topicName": "公式主项变换",
    "topicNameEn": "Change of Subject",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2018 DSE A1 Q1",
    "titleZh": "公式主项变换",
    "titleEn": "Change of Subject",
    "questionZh": "化 $b$ 为公式 $\\frac{a+4}{3} = \\frac{b+1}{2}$ 的主项。",
    "questionEn": "Make $b$ the subject of the formula $\\frac{a+4}{3} = \\frac{b+1}{2}$.",
    "solutionZh": [
      { "step": "$2(a+4) = 3(b+1)$", "mark": "1M", "desc": "交叉相乘消去分母" },
      { "step": "$2a + 8 = 3b + 3 \\implies 3b = 2a + 5$", "mark": "1M", "desc": "展开并移项" },
      { "step": "$b = \\frac{2a+5}{3}$", "mark": "1A", "desc": "求得 $b$ 的主项表达式" }
    ],
    "solutionEn": [
      { "step": "$2(a+4) = 3(b+1)$", "mark": "1M", "desc": "Cross multiply" },
      { "step": "$2a + 8 = 3b + 3 \\implies 3b = 2a + 5$", "mark": "1M", "desc": "Expand and isolate $3b$" },
      { "step": "$b = \\frac{2a+5}{3}$", "mark": "1A", "desc": "Express $b$ as subject" }
    ],
    "pitfallsZh": "展开 $3(b+1)$ 时得到 $3b+3$，不要漏乘常数项 1。",
    "pitfallsEn": "Don't forget to multiply 3 to both terms inside $(b+1)$.",
    "finalAnswer": "b = (2a + 5) / 3"
  },
  {
    "id": "2017_Q1",
    "year": 2017,
    "qNum": "Q1",
    "topicId": 1,
    "topicName": "公式主项变换",
    "topicNameEn": "Change of Subject",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2017 DSE A1 Q1",
    "titleZh": "公式主项变换",
    "titleEn": "Change of Subject",
    "questionZh": "化 $y$ 为公式 $k = \\frac{3x-y}{y}$ 的主项。",
    "questionEn": "Make $y$ the subject of the formula $k = \\frac{3x-y}{y}$.",
    "solutionZh": [
      { "step": "$ky = 3x - y$", "mark": "1M", "desc": "两边同乘以 $y$" },
      { "step": "$ky + y = 3x$", "mark": "1M", "desc": "含 $y$ 的项移到同一侧" },
      { "step": "$y(k+1) = 3x \\implies y = \\frac{3x}{k+1}$", "mark": "1A", "desc": "提取 $y$ 并求解" }
    ],
    "solutionEn": [
      { "step": "$ky = 3x - y$", "mark": "1M", "desc": "Multiply both sides by $y$" },
      { "step": "$ky + y = 3x$", "mark": "1M", "desc": "Group $y$ terms on LHS" },
      { "step": "$y(k+1) = 3x \\implies y = \\frac{3x}{k+1}$", "mark": "1A", "desc": "Factor out $y$ and solve" }
    ],
    "pitfallsZh": "提取公因式时 $ky+y = y(k+1)$，不要漏掉 $+1$。",
    "pitfallsEn": "Remember the $+1$ when factoring $ky+y$ into $y(k+1)$.",
    "finalAnswer": "y = 3x / (k + 1)"
  },
  {
    "id": "2016_Q1",
    "year": 2016,
    "qNum": "Q1",
    "topicId": 2,
    "topicName": "指数律",
    "topicNameEn": "Laws of Indices",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2016 DSE A1 Q1",
    "titleZh": "指数律化简",
    "titleEn": "Laws of Indices",
    "questionZh": "化简 $\\frac{(x^8 y^7)^2}{x^5 y^{-6}}$，并以正指数表示答案。",
    "questionEn": "Simplify $\\frac{(x^8 y^7)^2}{x^5 y^{-6}}$ and express your answer with positive indices.",
    "solutionZh": [
      { "step": "分子 $= x^{16} y^{14}$", "mark": "1M", "desc": "展开分子次方" },
      { "step": "原式 $= x^{16-5} y^{14-(-6)}$", "mark": "1M", "desc": "同底数指数相减" },
      { "step": "$= x^{11} y^{20}$", "mark": "1A", "desc": "化简得最终结果" }
    ],
    "solutionEn": [
      { "step": "Numerator $= x^{16} y^{14}$", "mark": "1M", "desc": "Expand power on top" },
      { "step": "Expression $= x^{16-5} y^{14-(-6)}$", "mark": "1M", "desc": "Subtract indices" },
      { "step": "$= x^{11} y^{20}$", "mark": "1A", "desc": "Final positive index result" }
    ],
    "pitfallsZh": "$14 - (-6) = 20$，减去负数相当于加上正数。",
    "pitfallsEn": "$14 - (-6) = 20$, subtracting a negative is adding a positive.",
    "finalAnswer": "x^11 * y^20"
  },
  {
    "id": "2015_Q1",
    "year": 2015,
    "qNum": "Q1",
    "topicId": 2,
    "topicName": "指数律",
    "topicNameEn": "Laws of Indices",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2015 DSE A1 Q1",
    "titleZh": "指数律化简",
    "titleEn": "Laws of Indices",
    "questionZh": "化简 $\\frac{m^9}{(m^3 n^7)^5}$，并以正指数表示答案。",
    "questionEn": "Simplify $\\frac{m^9}{(m^3 n^7)^5}$ and express your answer with positive indices.",
    "solutionZh": [
      { "step": "分母 $= m^{15} n^{35}$", "mark": "1M", "desc": "展开分母括号" },
      { "step": "原式 $= m^{9-15} n^{-35} = m^{-6} n^{-35}$", "mark": "1M", "desc": "同底数指数相减" },
      { "step": "$= \\frac{1}{m^6 n^{35}}$", "mark": "1A", "desc": "化为正指数表示" }
    ],
    "solutionEn": [
      { "step": "Denominator $= m^{15} n^{35}$", "mark": "1M", "desc": "Expand denominator" },
      { "step": "Expression $= m^{9-15} n^{-35} = m^{-6} n^{-35}$", "mark": "1M", "desc": "Subtract powers" },
      { "step": "$= \\frac{1}{m^6 n^{35}}$", "mark": "1A", "desc": "Express in positive index form" }
    ],
    "pitfallsZh": "$m$ 的次方在分母 $15 > 9$，因此留在大分母下为 $m^6$。",
    "pitfallsEn": "$m^{15}$ is larger in the denominator, leaving $m^6$ in the denominator.",
    "finalAnswer": "1 / (m^6 * n^35)"
  },
  {
    "id": "2014_Q1",
    "year": 2014,
    "qNum": "Q1",
    "topicId": 2,
    "topicName": "指数律",
    "topicNameEn": "Laws of Indices",
    "difficulty": "Easy",
    "marks": 3,
    "yearRef": "2014 DSE A1 Q1",
    "titleZh": "指数律化简",
    "titleEn": "Laws of Indices",
    "questionZh": "化简 $\\frac{(xy^{-2})^3}{y^4}$，并以正指数表示答案。",
    "questionEn": "Simplify $\\frac{(xy^{-2})^3}{y^4}$ and express your answer with positive indices.",
    "solutionZh": [
      { "step": "分子 $= x^3 y^{-6}$", "mark": "1M", "desc": "展开分子次方" },
      { "step": "原式 $= x^3 y^{-6-4} = x^3 y^{-10}$", "mark": "1M", "desc": "合并底数为 $y$ 的指数" },
      { "step": "$= \\frac{x^3}{y^{10}}$", "mark": "1A", "desc": "转换为正指数形式" }
    ],
    "solutionEn": [
      { "step": "Numerator $= x^3 y^{-6}$", "mark": "1M", "desc": "Expand numerator power" },
      { "step": "Expression $= x^3 y^{-6-4} = x^3 y^{-10}$", "mark": "1M", "desc": "Subtract powers for base $y$" },
      { "step": "$= \\frac{x^3}{y^{10}}$", "mark": "1A", "desc": "Express answer with positive indices" }
    ],
    "pitfallsZh": "注意指数相减为 $-6 - 4 = -10$，移至分母得 $y^{10}$。",
    "pitfallsEn": "Exponent subtraction is $-6 - 4 = -10$, move to denominator as $y^{10}$.",
    "finalAnswer": "x^3 / y^10"
  }
]
