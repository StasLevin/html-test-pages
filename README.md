# html-test-pages

https://sroei.github.io/html-test-pages/table.html


solution:
column_number = Array.from(document.getElementsByTagName('th')).find(th => th.textContent.toLowerCase().includes('three')).cellIndex

document.getElementsByTagName('td')[column_number].querySelector('button').click()


![image](https://github.com/user-attachments/assets/fdeb5074-ebe0-43d8-afea-21f3668a23d0)
