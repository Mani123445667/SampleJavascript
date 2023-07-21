# SampleJavascript



const randomNumbers = [27, 64, 47, 78, 48, 11, 76, 25, 11, 83];
function maxFromArray(numbers) {
    let max = numbers;
    for (let i = 1; i < numbers.length; i++) {
        if (i > max) {
            max = numbers[i];
        }
        }return(max);
}
    console.log(maxFromArray(randomNumbers));
