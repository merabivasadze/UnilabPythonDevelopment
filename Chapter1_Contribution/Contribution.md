## Fork this repository
<img align="right" width="300" src="https://github.com/firstcontributions/first-contributions/blob/master/assets/fork.png" alt="fork this repository" />

პროექტზე კოლექტიურად სამუშაოდ დაფორკეთ ეს რეპოზიტორია. ამისთვის დააჭირეთ fork ღილაკს გვერდის ზედა მარჯვენა ზოლში.
ამ რიგად თქვენს ანგარიშზე გაჩნდება რეპოზიტორიის ასლი.

## Clone the repository

<img align="right" width="300" src="https://github.com/firstcontributions/first-contributions/blob/master/assets/clone.png" alt="clone this repository" />

საკუთარ ანგარიშზე გაჩენილი დაფორკილი რეპოზიტორია გადაიტანეთ/დაკლონეთ თქვენს მოწყობილობაში. ამისთვის თქვენს ანგარიშზე გახსენით დაფორკილი რეპოზიტორია, დააჭირეთ clone ღილაკს და *copy to clipboard* იკონს.

თქვენს სამუშაო გარემოში გახსენით ტერმინალი და ჩააკოპირეთ შემდეგი გიტ კომანდი:

```
git clone <მისამართი რომელიც დააკოპირეთ კლონირებისთვის>
```
"<>"- სიმბოლოების წაშლით და ქლიფბორდში დაკოპირებული მისამართის ჩასმით მიიღებთ ბრძანების საბოლოო სახეს.

<img align="right" width="300" src="https://github.com/firstcontributions/first-contributions/blob/master/assets/copy-to-clipboard.png" alt="copy URL to clipboard" />

მაგალითისთვის, თქვენგან დაფორკილ ამ რეპოზიტორიის მისამართს ექნება შემდეგნაირი სახე:
```
git clone https://github.com/this-is-you/firstrepo.git
```
სადაც `this-is-you` არის თქვენი GitHub username. ამ რიგად თქვენ აკოპირებთ პირველი რეპოზიტორიის თქვენ მიერ დაფორკილ ვერსიას
სამუშაო მოწყობილობაზე.

## Create a branch

იმისთვის რომ უკეთ ჩასწვდეთ ბრენჩის როლს და მნიშვნელობას, [გაეცანით ოფიციალურ დოკუმენტაციას Branch თემაზე](https://github.com/firstcontributions/first-contributions/blob/master/).

სამუშაო გარემოში, ტერმინალი გადაიყვანეთ გადმოწერილი რეპოზიტორიის დირექტორიაში/საქაღალდის მისამართზე.

იმ შემთხვევაში თუ უკვე იქ არ იმყოფებით, გამოიყენეთ შემდეგი ბრძანება:

```
cd firstrepo
```
ახლა კი შევქმნათ ახალი ტოტი/branch `git checkout` ბრძანების გამოყენებით:
```
git checkout -b <add-your-new-branch-name>
```

სადაც `add-your-new-branch-name` შეიძლება იყოს ნებისმიერი სახელი, რომლითაც ტოტზე შესასრულებელ სამუშაოს ლაკონურად აღწერთ, მაგალითად:
```
git checkout -b adding-my-code
```


## გავავკეთოთ პროექტში ცვლილება და დავაკომიტოთ სამუშაოს დასრულებისას

მას შემდეგ რაც გაამზადებთ პროექტს თქვენს მოწყობილობაში, დაამატეთ დირექტორიას თქვენი კოდი და პროექტის აღწერა /firstProjects საქაღალდეში საკუთარი საქაღალდის შექმნით. 

საქაღალდის დასახელება `/სახელი_გვარი` ფორმატით გაამზადეთ, ხოლო ფაილები: `readme.md`, `app.py` დასახელებებით. 
```
firstrepo
│
│   some_files   
│
└─── firstProject
│   └─── temur_chichua
│       │   app.py
│       │   readme.md
```

ამის შემდეგ გახსენით დირექტორიის საწყის დონეზე განთავსებული README.md ფაილი და ქვემოთ მოცემულ _კონტრიბუტორები_ გრაფაში განათავსეთ თქვენი სახელი, გიტჰაბის მისამართი, პროექტის დასაღელება და პროექტის readme.mdის მისამართი, როგორც შაბლონზეა ნაჩვენები.

<img align="right" width="450" src="https://github.com/firstcontributions/first-contributions/blob/master/assets/git-status.png" alt="git status" />

თუ პროექტის დირექტორიაში გაუშვებთ ბრძანებას `git status`, როგორც მაგალითზეა ნაჩვენები, გამოჩნდება თქვენს მიერ დამატებული ფაილები რომელიც არ არის დამატებული გიტის რეპოზიტორიაში.


მათ რეპოზიტორიაში დასამატებლად უნდა გამოვიყენოთ `git add` ბრძანება:

```
git add .
```

ბრძანებაში `.` რეპოზიტორიაში დაამატებს დირექტორიაში არსებულ ყველა იმ ფაილს რომელიც არ არის გამოყოფილი .gitignore ფაილში.

აუცილებელია დავაკომიტოთ პროექტში შეტანილი ცვლილებები `git commit` ბრძანების გამოყენებით.:
```
git commit -m "დავამატე ჩემი პროგრამა და <your-name> კონტრიბუტორთა სიაში"
```
შეცვალეთ `<your-name>` თქვენი სახელით. ბრჭყალებში მითითებული ტექსტი უნდა ასახავდეს კომიტის მიზანს, ანუ ორ სიტყვიან შეჯამებას
თუ რა ცვლილებები მოხდა ამ ნაბიჯზე.

## Push changes to GitHub

საბოლოოდ საჭიროა ავტვირთოთ პროექტში ლოკალურად შეტანილი ცვლილებები ქლაუდზე, `git push` ბრძანების მეშვეობით:
```
git push origin <add-your-branch-name>
```
შეცვალე `<add-your-branch-name>` სახელით რომელიც თქვენი ტოტის/branch-ის შექმნისთვის გამოიყენეთ..

## Submit your changes for review

თქვენს GitHub რეპოზიტორიაში შეამჩნევთ  `Compare & pull request` ღილაკი. გააქტიურეთ ღილაკი მასზე დაჭერით.

<img style="float: right;" src="https://github.com/firstcontributions/first-contributions/blob/master/assets/compare-and-pull.png" alt="create a pull request" />

დაასაბმითეთ თქვენს მიერ გაკეთებული pull მოთხოვნა.

<img style="float: right;" src="https://github.com/firstcontributions/first-contributions/blob/master/assets/submit-pull-request.png" alt="submit pull request" />

თქვენი მოთხოვნის ნახვის შემდეგ მე შევძლებ გავაერთიანო/merge თქვენი კონტრიბუცია მთელს პროექტთან. ჩემს ქმედებაზე შეტყობინება მოგივათ მეილზე და შეტყობინებებში, რის შემდეგაც თქვენს მიერ შეტანილი ცვლილება გამოჩნდება პროექტის მასტერ ბრენჩზე.

### გილოცავ! 

თუ ყველა საფეხური შეასრულე შენ წარმატებით გაიარე სტაჟირების პირველი ეტაპი.
