number_to_word
==============
echo convert_number_to_words(123456789);
// one hundred and twenty-three million, four hundred and fifty-six thousand, seven hundred and eighty-nine

echo convert_number_to_words(123456789.123);
// one hundred and twenty-three million, four hundred and fifty-six thousand, seven hundred and eighty-nine point one two three

echo convert_number_to_words(-1922685.477);
// negative one million, nine hundred and twenty-two thousand, six hundred and eighty-five point four seven seven

// float rounding can be avoided by passing the number as a string
echo convert_number_to_words(123456789123.12345); // rounds the fractional part
// one hundred and twenty-three billion, four hundred and fifty-six million, seven hundred and eighty-nine thousand, one hundred and twenty-three point one two
echo convert_number_to_words('123456789123.12345'); // does not round
// one hundred and twenty-three billion, four hundred and fifty-six million, seven hundred and eighty-nine thousand, one hundred and twenty-three point one two three four five
