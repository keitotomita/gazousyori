課題２
２階調画像の生成
IMG = ORG>128;
imagesc(IMG); colormap(gray); colorbar;  axis image;
pause;
によってできた図を図1に示す。
![2-1](https://github.com/keitotomita/gazousyori/blob/master/2-1.png)
図１．2階調画像
４階調画像の生成
IMG0 = ORG>64;
IMG1 = ORG>128;
IMG2 = ORG>192;
IMG = IMG0 + IMG1 + IMG2;
imagesc(IMG); colormap(gray); colorbar;  axis image;
によってできた図を図２に示す。
![2-2](https://github.com/keitotomita/gazousyori/blob/master/2-2.png)
図２．4階調画像
