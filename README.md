# ar-rocket-css

-   클론코딩
-   Online Tutorials - CSS Animation Effects | Neumorphism Effect with Soft Gradient & Animated Rocket | FontAweosme
-   [Link](https://www.youtube.com/watch?v=41tNotMxu1A)

## 결과물

![](result.gif)

## 배운점

-   box-shadow 에서 option으로 존재하는 inset 은 볼록을 오목으로 바꾼다.
-   **inset을 0**으로 설정하면 ::before 에서 content: ''를 설정해야 보이듯이, 부모 사이즈가 된다.
-   `-webkit-text-stroke: 2px #000;`통해서 `<i>`로 된 font-awesome icon에 테두리를 줄 수 있다.
-   `<i class="fas fa-cloud" style="--i:0;"></i>`와 같이 속성을 주고
    -   css에서 `animation-delay: calc(-0.5s * var(--i));` 와 같이 속성을 줄 수 있다.
