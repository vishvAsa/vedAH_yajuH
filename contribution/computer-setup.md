+++
title = "Computer setup"
unicode_script = "devanagari"
+++

## समानं कर्म
- अधः XYZ इति यद् अस्ति, तस्य स्थाने स्वीयं github-नाम प्रयुङ्क्ताम्।
- https://github.com/XYZ/vedAH इति पूर्वम् एव वर्तते चेन् निष्कासयतु browser-उपयोगेन।
- https://github.com/vvasuki/vedAH इत्यत्र गत्वा पुनः fork इति करोतु। https://github.com/XYZ/vedAH इति किञ्चिल् लभ्यते।

## Windows setup

ततः (`F:\Git` इति यथापेक्षं परिवर्त्य)-

```
cd F:\Git\

git clone --single-branch --depth 1 --branch content https://github.com/XYZ/vedAH.git vedAH-content
git clone --single-branch --depth 1 --branch static_files https://github.com/XYZ/vedAH.git vedAH-static
git clone --single-branch --depth 1 --branch master https://github.com/XYZ/vedAH.git vedAH-master

cd f:\Git\vedAH-static
git remote add upstream https://github.com/vvasuki/vedAH.git
git pull upstream static_files

cd f:\Git\vedAH-content
git remote add upstream https://github.com/vvasuki/vedAH.git
git pull upstream content

rmdir /S F:\Git\vedAH-master\content
rmdir /S F:\Git\vedAH-master\static
mklink /s F:\Git\vedAH-master\content F:\Git\vedAH-content
mkdir F:\Git\vedAH-master\static
mklink /s F:\Git\vedAH-master\static F:\Git\vedAH-static\*
```

### Stuff which won't work
```
mklink /s F:\Git\vedAH-master\static F:\Git\vedAH-static\
f:\Git\vedAH-master>hugo.exe server --renderToDisk
Error: add site dependencies: create deps: create PathSpec: build filesystems: create main fs: symlinks not allowed in this filesystem

f:\Git>mklink /h F:\Git\vedAH-master\content F:\Git\vedAH-content
Access is denied.
```

## Linux setup
```
cd ~/git_projects/

git clone --single-branch --depth 1 --branch content https://github.com/XYZ/vedAH.git vedAH-content
git clone --single-branch --depth 1 --branch static_files https://github.com/XYZ/vedAH.git vedAH-static
git clone --single-branch --depth 1 --branch master https://github.com/XYZ/vedAH.git vedAH-master

cd ~/git_projects/vedAH-static
git remote add upstream https://github.com/vvasuki/vedAH.git
git pull upstream static_files

cd ~/git_projects/vedAH-content
git remote add upstream https://github.com/vvasuki/vedAH.git
git pull upstream content

rm -rf ~/git_projects/vedAH-master/content
rm -rf ~/git_projects/vedAH-master/static
ln -s ~/git_projects/vedAH-content ~/git_projects/vedAH-master/content 
ln -s ~/git_projects/vedAH-static ~/git_projects/vedAH-master/static 
```

## सञ्चिकासु प्राप्तासु सत्सु कार्यम्
- यदि कार्यम् vedAH-content इत्यस्मिन् क्रियते
  - `git pull upstream content` इति परिवर्तनानि लभ्यानि।
  - ततो नुदित्वाकर्षणाभ्यर्थनं https://github.com/XYZ/vedAH/tree/content इत्यत्र गत्वा प्रेषणीयम्।
- यदि कार्यम् vedAH-static इत्यस्मिन् क्रियते
  - `git pull upstream static_files` इति परिवर्तनानि लभ्यानि।
  - ततो नुदित्वाकर्षणाभ्यर्थनं https://github.com/XYZ/vedAH/tree/static इत्यत्र गत्वा प्रेषणीयम्।
