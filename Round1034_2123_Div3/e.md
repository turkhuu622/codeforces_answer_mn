$c_v$-ээр $a_i=v$ байх $i$-ийн тоог тэмдэглэе. Хэдэн ч үйлдэл хийсэн $a$-ийн MEX нь ихсэхгүй. $0 \le m \le MEX(a)$ байх $m$-ийн хувьд $k$-ийн ямар утгууд дээр $a$-ийн MEX-г $m$ болгож чадахыг олъё.

$c_m \le k$ (бүх $m$-үүдийг устгах ёстой) ба $k \le n-m$ (0,1,...,m-1 үүдээс ядаж ганц ганц үлдэх ёстой) ба эдгээр нөхцөлийг хангах ямар ч $k$-ийн хувьд чадна. Эдгээр бүх утгуудаар гүйгээд хариун дээр нь 1-ийг нэмээд явбал хугацаандаа амжихгүй.

Анх 0-ээр дүүргэсэн $s$ массив аваад $s[c_m]$++, $s[n-m+1]$-- гээд хийсний дараа $k$-ийн хувьд хариу нь $s[1]+s[2]+...+s[k]$ байна.

**Time complexity: $O(n)$**\
[Submission](https://codeforces.com/contest/2123/submission/326839880)