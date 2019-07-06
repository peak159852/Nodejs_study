HTML - Form

<form action="http://localhost:3000/process_create" method="post">
    <p><input type="text" name="title"></p>
    <p>
      <textarea name="description"></textarea>
    </p>
    <p>
      <input type="submit">
    </p>
  </form>

  form 태그 , input 태그 , textarea 태그

  form 태그 안의 method , 기본 get , post지정 
  post 는 url 숨김

  input 태그 안에 name 값 지정해주기
  type submit 제출