<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lab 4 Assignment</title>
</head>
<body>
    <script>
        // Task 1: Create an array named trees with specified values
        var trees = ['Sugar Maple', 'Red Maple', 'Red Oak', 'American Beech', 'Flowering Dogwood', 'Eastern Redbud'];

        // Task 2: Output the array values using a for loop
        document.writeln('<br><br>For Loop Output:<br>');
        for (var i = 0; i < trees.length; i++) {
            document.writeln(trees[i] + '<br>');
        }

        // Task 3: pop() the last value and then output the array
        trees.pop();
        document.writeln('<br>Array after pop():<br>');
        document.writeln(trees + '<br>');

        // Task 4: push() the value 'Magnolia' onto the array and output it
        trees.push('Magnolia');
        document.writeln('<br>Array after push("Magnolia"):<br>');
        document.writeln(trees + '<br>');

        // Task 5: Output the length of the array using the length property
        document.writeln('<br>Length of the array:<br>');
        document.writeln(trees.length + '<br>');

        // Task 6: Sort the array and then output all of the values
        trees.sort();
        document.writeln('<br>Sorted array:<br>');
        document.writeln(trees.join('<br>') + '<br>');

        // Task 7: Create an array called numbers with specified values
        var numbers = [4, 8, 2, 9, 10, 12, 3, 5];

        // Task 8: Use a loop to calculate the average and output it
        var sum = 0;
        for (var j = 0; j < numbers.length; j++) {
            sum += numbers[j];
        }
        var average = sum / numbers.length;
        document.writeln('<br>Average of numbers array:<br>');
        document.writeln(average + '<br>');

        // Task 9: Use a loop to calculate the sum and output it
        document.writeln('<br>Sum of numbers array:<br>');
        document.writeln(sum + '<br>');

        // Task 10: Sort the array and output the values
        numbers.sort(function(a, b) {
            return a - b;
        });
        document.writeln('<br>Sorted numbers array:<br>');
        document.writeln(numbers.join('<br>') + '<br>');
    </script>
</body>
</html>
