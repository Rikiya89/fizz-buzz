# fizz-buzz
 
This code uses the p5.js library to create a canvas and display a series of messages that change based on the value of the frameCount variable, which increases by 1 for each frame that is drawn.

The canvas is set up in the setup() function, which specifies the size of the canvas (400 pixels by 400 pixels), sets the text alignment to be centered horizontally and vertically, sets the font size to 72 pixels, and disables the stroke for drawing shapes. The frameRate() function is also called to set the frame rate of the animation to 5 frames per second.

The draw() function is called repeatedly in a loop and is where the main logic of the program is implemented.

The first variable declared is message which is used to store the message that will be displayed on the canvas.

The program then checks whether the frameCount variable is divisible by 3 and/or 5 using the modulo operator (%). If it is divisible by both 3 and 5, the canvas is set to a red background and the text color is black. The message variable is set to "Fizz Buzz". If it is only divisible by 3, the background is set to green and the message is set to "Fizz". If it is only divisible by 5, the background is set to blue and the message is set to "Buzz". If it is not divisible by either 3 or 5, the background is set to a dark gray and the message is set to the value of frameCount.

Finally, the text() function is called to display the message on the canvas in the center of the screen.

Overall, this program implements the FizzBuzz problem, which is a classic programming challenge that involves printing a series of numbers from 1 to a given limit, but printing "Fizz" for multiples of 3, "Buzz" for multiples of 5, and "FizzBuzz" for multiples of both 3 and 5. In this particular implementation, the program uses an animation to display the messages and the limit of the sequence is not specified.


このコードはp5.jsライブラリを使用して、キャンバスを作成し、フレームカウント変数の値に基づいて変化する一連のメッセージを表示します。フレームカウント変数は、描画されるフレームごとに1ずつ増加します。

キャンバスはsetup()関数で設定され、キャンバスのサイズ（400ピクセル×400ピクセル）、テキストの水平および垂直中央揃え、フォントサイズ72ピクセル、ストロークを無効にするよう指定されています。また、アニメーションのフレームレートを1秒あたり5フレームに設定するためにframeRate()関数が呼び出されています。

draw()関数は繰り返し呼び出され、プログラムのメインの論理を実装します。

最初に宣言される変数は message で、キャンバスに表示されるメッセージを格納するために使用されます。

次に、プログラムはフレームカウント変数が3と/または5で割り切れるかどうかを、剰余演算子（%）を使用してチェックします。3と5の両方で割り切れる場合、キャンバスの背景色を赤に設定し、テキストの色を黒にします。message変数は "Fizz Buzz" に設定されます。3でのみ割り切れる場合、背景を緑に設定し、messageを "Fizz" に設定します。5でのみ割り切れる場合、背景を青に設定し、messageを "Buzz" に設定します。どちらでも割り切れない場合、背景色を暗いグレーに設定し、messageはframeCountの値に設定されます。

最後に、text()関数が呼び出されて、メッセージが画面の中央に表示されます。

このプログラムは、FizzBuzz問題を実装しており、クラシックなプログラミングチャレンジの1つで、与えられた限界値までの数列を表示することを目的としています。ただし、3の倍数の場合には "Fizz"、5の倍数の場合には "Buzz"、両方の場合には "FizzBuzz" を表示する必要があります。この特定の実装では、プログラムはアニメーションを使用してメッセージを表示し、数列の上限は指定されていません。
