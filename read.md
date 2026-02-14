Pseudo-class (:) — holatga qarab style berish

hover ustiga sichqoncha borganda stylelari ozgarishi

input:focus input ichiga kursor qoyilganda

button:active yani bolsilgan ishlaydi

li:first-child birinchi farzand bolib kelganda. ishlaydi
li:last-child songi farzandni ushlash
li:nth-child(4) nechinchi farzandga style berish kerak bolsa
nth-child(odd) toqlari
nth-child(even) juftlari

:checked input checked bolganda
:disabled

//============================================

2️⃣ Pseudo-element (::) — elementning bir qismiga style berish

p::first-letter matnning birinchi harfi
p::first-line matnning birinchi qatori
p::selection {
background: yellow;
color: black;
}
kopiya olish uchun belgilaganda

after/ before

//=====================================================
CSS Combinators — elementlar orasidagi ALOQA

div p {
color: red;
} div ichidagi barcha p elementlarga tasir qiladi ota elementning barcha avlodlariga (bola, nevarasi, chevarasi va h.k.) t

Child (>) — faqat bevosita bola faqat birinchi darajali farzandlariga

Adjacent sibling (+) — yonidagi bitta

h2 + p {
color: green;
}

General sibling (~) — keyingi barcha aka-ukalar

h2 ~ p {
color: orange;
}

h2 dan keyin kelgan barcha plar
