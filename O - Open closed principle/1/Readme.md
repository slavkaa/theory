# Open/closed principle
_Принцип відкритості/закритості_

Ми змінили поведінку класу Auth не переписуючі ані його код, ані код інших классів.
Достатньо було просо дадати клас FileLogger.

Є  думка що метод застарів і актуальний лише за відсутності 100% покриття классу юніт тестами.