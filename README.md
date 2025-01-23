# tawjihee

<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>حساب المعدل</title>
</head>
<body>
    <script>
        // الكود الذي كتبته هنا
        var x=0, y=0, z=0, q=0, w=0, e=0, r=0, t=0, p=0;
        x = parseInt(prompt("علامة العربي: "));
        y = parseInt(prompt("علامة الإنجليزي: "));
        z = parseInt(prompt("علامة التاريخ: "));
        q = parseInt(prompt("علامة التربية الإسلامية: "));
        w = parseInt(prompt("المادة 1 : "));
        e = parseInt(prompt("المادة 2 : "));
        r = parseInt(prompt("المادة 3 : "));
        t = parseInt(prompt("المادة 4 : "));
        var c=0, v=0, b=0, n=0, m=0, a=0, s=0, d=0;
        c=x; v=y; b=z; n=q; m=w; a=e; s=r; d=t;
        p = (w + e + r + t) / 8 * (70 / 100);
        x = x / 2  * (10 / 100);
        y = y / 2  * (10 / 100);
        z = z / 2 * (4 / 100);
        q = q / 2  * (6 / 100);
        t = x + y + z + q + p;
        document.write("<pre>");
        document.write("____________________\n");
        document.write("| التاريخ    :   " + b + " |\n");
        document.write("| الدين     :   " + n + " |\n");
        document.write("| الإنجليزي  :   " + v + " |\n");
        document.write("| العربي    :   " + c + " |\n");
        document.write("| المادة 1   :   " + m + " |\n");
        document.write("| المادة 2   :   " + a + " |\n");
        document.write("| المادة 3   :   " + s + " |\n");
        document.write("| المادة 4   :   " + d + " |\n");
        document.write("____________________\n");
        document.write(" معدلك : " + t + " معدلك من 100\n");
        document.write("</pre>");
    </script>
</body>
</html>
