# Denis Bogdan

## Contacts:

- tel: +375 29 689-50-48
- Telegram: D_Bogdan
- Mail: <thespirit3000@gmail.com>
- Github: @thespirit3000

## Summary

I have been working as telecommunications engineer for the last 9 years. My responsibilities include setup, launch and service fire safety systems, security systems and CCTV systems. I took part in  such projects as Minsk International Airport, Belorussian Cement Company.  
I am interesting in web-development and my goal for this course is to take structured knowledge and experience in web-development to change my career. I hope to get the opportunity to work with a mentor so that he guides me in my training.  
My current work requires regular learning new technologies and equipments and I have good self-organization and self-learning abilities.

## Skills:

- Python programming skills;
- JS programming skills;
- HTML/CSS;
- LESS/SASS skills;
- Git;
- Photoshop, gimp, krita;
- Figma/ PSDetch;
- VIM/EMACS as text editors;
- VScode/Atom;
- Fedora linux as workstation (i3 as DE);
- Googling skills );

### Code examples:

``` python
def checkio(data):
    result = []
    if 0<len(data)<1000:
        for el in data:
            if data.count(el) > 1:
                result.append(el)
        print('checkio('+str(data)+') == '+str(result))
    else:
        print('некоректное кол-во элементов')
    return result
```

``` python
def long_repeat(line):
    """
        length the longest substring that consists of the same char
    """
    if len(line) == 0:
        return 0
    else:
        list = []
        i = 0
        index_list = 0
        list.append(line[0])
        max = 0
        for i in range(1, len(line)):
            if line[i] == line[i-1]:
                list[index_list] += line[i]
            else:
                index_list += 1
                list.append(line[i])
        for i in list:
            if len(i) > max:
                max = len(i)
        print(list, max)
    return max

```

### Experience:

- coding in course at [pythontutor](https://pythontutor.ru/);
- practice at [checkio.org](https://py.checkio.org/user/thespirit3000/);
- some practice whith HTML/CSS layout;

### Education

- High grade education at Mogilev State  University of Food Technologies with Low Temperature Technology specialization;
- programming course at [pythontutor](https://pythontutor.ru/);
- HTML/CSS codeacademy;
- learning programming, Photoshop, HTML/CSS by youtube lessons and courses;

### English

I can read technic documents and literature in english.
