显示一个简单的加载进度条动画
由 FireStar0507 编写
参数：
1. nums (int): 进度条的总长度，即显示的 '#' 字符的数量。
2. sleeptime (float, optional): 每次迭代之间的睡眠时间（秒）。默认值为 0.5 秒。
3. step (int, optional): 每次迭代的步长，表示每次增加的 '#' 字符数量。默认值为 1。
4. loaded (str, optional): 用于代表已加载部分的字符。默认值为 '#'。
5. noloaded (str, optional): 用于代表未加载部分的字符。默认值为 '-'。
示例：
loading(18, 0.5, 2, "$", "!") 将会创建一个长度为 18 的进度条，每过0.5

Displays a simple loading progress bar animation
Written by FireStar0507
Parameter:
1. nums (int): The total length of the progress bar, i.e. the number of '#' characters displayed.
2. sleeptime (float, optional): The sleep time (seconds) between each iteration. The default value is 0.5 seconds.
3. step (int, optional): The step size of each iteration, indicating the number of '#' characters that are added each time. The default value is 1.
4. loaded (str, optional): Used to represent the loaded part. The default value is '#'.
5. noloaded (str, optional): Used to represent the unloaded part. The default value is '-'.
Example:
loading(18, 0.5, 2, "$", "!") will create a progress bar of length 18 every 0.5
