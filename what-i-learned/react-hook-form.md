## userForm

### register 함수

input을 특정 이름과 옵션으로 등록하면 훅폼이 알아서 이벤트나 ref 관리해줌

```
const { onChange, onBlur, name, ref } = register('firstName');
// include type check against field path with the name you have supplied.

<input
  onChange={onChange} // assign onChange event
  onBlur={onBlur} // assign onBlur event
  name={name} // assign name prop
  ref={ref} // assign ref prop
/>
// same as above
<input {...register('firstName')} />

```
