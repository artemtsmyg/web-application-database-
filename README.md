Создал простое простое CRUD веб-приложение, в которое можно добавит Имя и Фамилию а также исправлять и удалять данные из базы. 
1) В класс UserRepository добавил метод public void deleteById(int id)(подсказка: SQL запрос "DELETE FROM userTable WHERE id=?", метод jdbc.update) - удаления записи пользователя из БД по ID.
2) В класс UserService добавил метод public void deleteById(int id)(подсказка: в нем вызывается метод userRepository.deleteById) - удаление пользователя через репозиторий.
3) В класс UserController добавил метод public String deleteUser(@PathVariable("id") int id)(с аннотацией: @GetMapping("user-delete/{id}")) (подсказка: в нем вызывается метод userService.deleteById)

![2024-07-13_00-33-22](https://github.com/user-attachments/assets/1137b123-ab70-48db-b4fd-a35fae05dab9)

![2024-07-13_00-33-46](https://github.com/user-attachments/assets/7a932a15-7c86-42c6-a154-7b16f92bb8f7)

![2024-07-13_00-34-08](https://github.com/user-attachments/assets/a45a5363-d268-4ecb-939f-687402e59acd)

![2024-07-13_00-34-28](https://github.com/user-attachments/assets/a6200617-58e5-49e9-9588-93a8c9c8a8b6)

![2024-07-13_00-34-43](https://github.com/user-attachments/assets/eb27ad4d-97e9-4378-b49e-08e658f545c7)

![2024-07-13_00-34-59](https://github.com/user-attachments/assets/ef6410ec-a03d-46fb-b0c5-2ef099340a7c)

![2024-07-13_00-35-10](https://github.com/user-attachments/assets/28d1d862-2e9c-4e5d-a34d-3a707435fb35)

![2024-07-13_00-35-47](https://github.com/user-attachments/assets/cca6e806-850d-4978-9d57-e90646bb8df3)

![2024-07-13_00-36-25](https://github.com/user-attachments/assets/f0423667-accd-4557-afd6-3bd0bbeff75e)

![2024-07-13_00-36-39](https://github.com/user-attachments/assets/89f181e8-8b87-43b1-84c7-f99665ec4b9d)














