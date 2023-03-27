# Развертывание

## Status
Accepted

## Context
Необходимо решение по развертыванию приложения, которое удовлетворяет следующим требованиям:
- просто
- быстро
Требования сформированы исходя из того, что заказчик не планирует развивать продукт, мы также не планируем им заниматься, поэтому строить инфраструктуру для развертывания - пустая трата средств

## Decision
В папках приложений создаем папку deploy со скриптами для развертывания

## Consequences
- надо заходить на машину для перевыкладки
- можно ошибиться
- при этом решение удовлетворяет составленным требованиям, поэтому принято командой