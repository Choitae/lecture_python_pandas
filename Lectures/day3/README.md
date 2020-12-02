# Day3

## 1. 리뷰

git과 파이썬 리뷰

1. git
 - 로컬 저장소
 - 리무트 저장소
2. Python
 - 기본 자료형
 - 조건문
 - 반복문

## 2. Python 과정

#### 반복문

#### 리스트

#### 튜플과 딕셔너리

---

## 3. 과제

#### `input()` 으로 영문 문장을 입력 받아 소문자별 합계를 출력한다.

예) 다음은 python doc 중 일부:

```
You should check for DeprecationWarning in your code
When Python 2.7 was still supported, a lot of functionality in Python 3 was kept for backward compatibility with Python 2.7. With the end of Python 2 support, these backward compatibility layers have been removed, or will be removed soon. Most of them emitted a DeprecationWarning warning for several years. For example, using collections.Mapping instead of collections.abc.Mapping emits a DeprecationWarning since Python 3.3, released in 2012.

Test your application with the -W default command-line option to see DeprecationWarning and PendingDeprecationWarning, or even with -W error to treat them as errors. Warnings Filter can be used to ignore warnings from third-party code.

Python 3.9 is the last version providing those Python 2 backward compatibility layers, to give more time to Python projects maintainers to organize the removal of the Python 2 support and add support for Python 3.9.

Aliases to Abstract Base Classes in the collections module, like collections.Mapping alias to collections.abc.Mapping, are kept for one last release for backward compatibility. They will be removed from Python 3.10.

More generally, try to run your tests in the Python Development Mode which helps to prepare your code to make it compatible with the next Python version.

Note: a number of pre-existing deprecations were removed in this version of Python as well. Consult the Removed section.
```

- 위 문장의 알파벳 소문자를 수를 센다. 결과로 각 소문자 문자 수를 문자별로 합계를 출력하시오. 

```
----------
a: 50
b: 20
...
z: 1
```

- 이때 string 메서드에서 isalpha, islower 를 사용해서 구현해 보시오.
 - 참조: https://seongjaemoon.github.io/python/2017/12/05/pythonStringFormat.html

