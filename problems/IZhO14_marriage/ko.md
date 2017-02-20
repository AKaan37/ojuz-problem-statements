옛날 옛적, 호랑이가 담배 물던 그 시절에, 승현이는 저 멀리 어딘가에서 왕을 하고 있었습니다. 승현이에게는 $M$명의 아름다운 딸들이 있었습니다. 마침내, 그녀들이 결혼해야 할 때가 왔습니다. 승현이는 $N$개의 이웃한 왕국들에게 편지를 보냈고, 각 왕국들은 승현이의 딸 중 한 명과 결혼을 하고자 하는 왕자를 한 명씩 보냈습니다.

딸들을 사랑하는 아버지로서 승현이는 딸들의 입장을 고려했습니다. 우선 승현이는 어린 남자들을 한 줄에 세워서 $1$번부터 $N$번까지 번호를 붙여서, 딸들에게 각각 자신이 결혼하고자 하는 왕자들의 후보를 받았습니다.

승현이는 수학적인 밑바탕이 잘 되어 있어서, 딸들이 원하는 왕자와 결혼하는 것이 가능한지 판정할 수 있습니다. 하지만 갑자기 승현이는 더 흥미로운 문제를 생각해 냈습니다: 번호가 $L$ 이상 $R$ 이하인 왕자들만 고려했을 때 각 딸에게 결혼할 왕자를 정해줄 할 수 있는 $(L, R)$ ($1 \le L \le R \le N$) 쌍의 수는 몇 개나 될까요?

승현이가 답을 찾을 수 있도록 도와주세요!

### 입력 형식

첫 번째 줄에 왕자의 수 $N (1 \le N \le 30 000)$, 딸들의 수 $M (1 \le M \le 2 000)$과 각 딸들이 후보로 지정한 왕자들의 수의 총 합 $K$ ($1 \le K \le \min(N \times M, 100 000)$)가 주어집니다.

다음 $K$개 줄에 두 개의 정수 $A_{i}$와 $B_{i}$가 주어집니다. ($1 \le A_{i} \le N, 1 \le B_{i} \le M$) 이는 $B_{i}$번 딸이 $A_{i}$번 왕자를 좋아한다는 것입니다. 모든 쌍은 서로 다릅니다.

### 출력 형식

딸들에게 결혼할 왕자를 정해줄 수 있는 $(L, R)$ 쌍의 개수를 출력합니다.

### 채점

각 테스트 케이스마다 점수가 주어집니다.

* 24%의 테스트 케이스에 대해 $N \le 10, M \le 4.$
* 48%의 테스트 케이스에 대해 $N \le 100, M \le 50.$
* 72%의 테스트 케이스에 대해 $N \le 1000, M \le 500.$

### 예제

<table class='table table-bordered table-condensed'>
 <thead>
  <tr>
   <th style="width: 50%;">입력</th>
   <th style="width: 50%;">출력</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td class="code-font">5 3 7<br/>
1 1<br/>
1 2<br/>
1 3<br/>
2 3<br/>
3 2<br/>
4 2<br/>
5 1</td>
   <td class="code-font">4</td>
  </tr>
 </tbody>
</table>

### 참고

예제에서는 $(1, 3), (1, 4), (1, 5), (2, 5)$가 가능합니다.