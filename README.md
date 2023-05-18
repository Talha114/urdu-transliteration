# Roman Urdu to Urdu Transliteration

This is a basic program for Roman Urdu to Urdu transliteration. It maps Urdu characters to their corresponding Roman Urdu equivalents using dictionaries and replaces them in the strings.

## Urdu Dictionary

The program uses the following Urdu dictionary to perform the transliteration:

```python
urduDict = {
    'آ':'ā',
    'ا':'a',
    'ب':'b',
    'پ':'p',
    'ت':'t',
    'ٹ':'ṭ',
    'ث':'s',
    'ج':'j',
    'چ':'c',
    'ح':'h',
    'خ':'x',       
    'د':'d',
    'ڈ':'ḍ',
    'ذ':'z',
    'ر':'r',
    'ڑ':'ṛ',
    'ز':'z',
    'ژ':'zh',
    'س':'s',
    'ش':'sh',
    'ص':'s',    
    'ض':'Ż',
    'ط':'t',
    'ظ':'z',
    'ع':'a',
    'غ':'g',
    'ف':'f',
    'ق':'q',
    'ک':'k',
    'گ':'g',
    'ل':'l',
    'م':'m',
    'ن':'n',
    'ں':'i',
    'و':'o',
    'ہ':'eh',
    'ھ':'h',         
    'ی':'y',    
    'ے':'e'
}
```

## Additional Dictionary

An additional dictionary `dict2` is used to handle certain words or phrases in the transliteration. For example:

```python
dict2 = {
    'hi': 'ھی',
    'sa': 'سا'
}
```

## Example Usage

Here's an example of how to use the program:

```python
str1 = 'یہی تو میں ان سے بھی کہہ رہا تھا'
result1 = urdu2roman(str1)
print(result1)
```

Output:
```
'یہی تو میں ان سے بھی کہہ رہا تھا'
```

```python
str2 = 'Jaisa ke sub ne dekha is team main kuch dum nazar aya sub ne achi performance di'
result2 = roman2urdu(str2)
print(result2)
```

Output:
```
'جاںثا کے ثب نے دےکحا ںث تےام ماںن کچح دم ناذار ایا ثب نے اچحں پےرفورمانچے دں'
```

Feel free to modify and use the code according to your needs. Happy transliterating!
