# CSS Flexbox:

- display: flex | inline-flex
- flex-direction: row | column
- flex-wrap: nowrap | wrap | wrap-reverse
- flex-basis: <length>
- justify-content (main axist/x): flex-start | flex-end | center | space-between | space-around | space-evenly; (evenly - khoang cach space deu nhau; around kc ke noi nhau nen ben trai+fai se =1/2 o item ben trong)
- justify-self: flex-start | flex-end | center
- align-content (cross axist/y): flex-start | flex-end | center
- align-self: flex-start | flex-end | center
- align-items: start | end;
- flex-grow: <number> 'ti le gian'
- flex-srink:<number>
- flex: flex-grow | flex-shrink | flex-basis
- flex-flow: flex-direction | flex-wrap
- order: <number>

# position:

- relative: lay no lam toa do goc, khong chiu anh huong cua phan tu khac; cung khong lam thay doi phan tu khac quanh no;
- absolute: lay phan tu gan nhat co 'position' lam toa do goc
- fixed: co dinh;
- sticky: bam dinh
  --> khi co position thi cac attr: top,left, bottom, right moi active;
  --> de full thi co the set: top = left = bottom = right = 0;

#background:

- dung ket hop image, linear-gradient lam mau nen; sd mau rgba() thi co do trong suot;
- dung color thi co background-clip: de xac dinh do lan mau; dung image thi dung background_origin de xac dinh;

# pseudo

++ pseudo-elements:

- tao items hien thi tren website ma ko can tao html, gom
- ::before | ::after | ::first-letter || ::first-line | ::selection

++ pseudo-class: (lop gia):

- :root | :hover | : active | :first-child | :last-child
  :root phan tu goc
  :hover: ho chuot
  :active dang hoat dong khi bam va giu chuot

# box-sizing:

- dung value: border-box -> tu dong tinh toan de size cua box khong tang len khi sd margin, padding, border

# background-size:cover;

    /* contain: lay chieu dai nhat co the; khong bi che khuat;
      cover: chon canh dai, nhung chap nhan viec che 1 phan img, khong chap nhan khoang trang - luon fill;
    */
