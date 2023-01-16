# module12.7.3
money = int(input('Ввод суммы: '))
per_cent = {'ТКБ': 5.6, 'СКБ': 5.9, 'ВТБ': 4.28, 'СБЕР': 4.0}
deposit = []
for value in per_cent.values():
   result = int(money / 100 * value)
   deposit.append(result)
#deposit.append(per_cent['ТКБ'])
#deposit.append(per_cent['СКБ'])
#deposit.append(per_cent['ВТБ'])
#deposit.append(per_cent['СБЕР'])
#deposit = [5600, 5900, 4280, 4000]
print('Максимальная сумма, которую вы можете заработать — ', max(deposit))
