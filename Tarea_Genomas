Genoma1 = open('AY274119.txt', 'r')
gen1 = Genoma1.read()
Genoma2 = open('AY278488.2.txt', 'r')
gen2 = Genoma2.read()
Genoma3 = open('MN908947.txt', 'r')
gen3 = Genoma3.read()
Genoma4 = open('MN988668.txt', 'r')
gen4 = Genoma4.read()
Genoma5 = open('MN988669.txt', 'r')
gen5 = Genoma5.read()


def comparar(x, y):
    n = 0
    for gen in range(len(x)):
        if x[gen] == y[gen]:
            n += 1
    return round((n * 100 / len(x)), 3)


print('{:^10}'.format('Genomas') + '{:>15}'.format('AY274119') + '{:>15}'.format('AY278488.2') + '{:>15}'.format(
    'MN908947') + '{:>15}'.format('MN988668') + '{:>15}'.format('MN988669'))
print('{:<10}'.format('AY274119') + '{:>15}'.format(comparar(gen1, gen1)) + '{:>15}'.format(
    comparar(gen1, gen2)) + '{:>15}'.format(comparar(gen1, gen3)) + '{:>15}'.format(
    comparar(gen1, gen4)) + '{:>15}'.format(comparar(gen1, gen5)))
print('{:<10}'.format('AY278488.2') + '{:>15}'.format(comparar(gen2, gen1)) + '{:>15}'.format(
    comparar(gen2, gen2)) + '{:>15}'.format(comparar(gen2, gen3)) + '{:>15}'.format(
    comparar(gen2, gen4)) + '{:>15}'.format(comparar(gen2, gen5)))
print('{:<10}'.format('MN908947') + '{:>15}'.format(comparar(gen3, gen1)) + '{:>15}'.format(
    comparar(gen3, gen2)) + '{:>15}'.format(comparar(gen3, gen3)) + '{:>15}'.format(
    comparar(gen3, gen4)) + '{:>15}'.format(comparar(gen3, gen5)))
print('{:<10}'.format('MN988668') + '{:>15}'.format(comparar(gen4, gen1)) + '{:>15}'.format(
    comparar(gen4, gen2)) + '{:>15}'.format(comparar(gen4, gen3)) + '{:>15}'.format(
    comparar(gen4, gen4)) + '{:>15}'.format(comparar(gen4, gen5)))
print('{:<10}'.format('MN988669') + '{:>15}'.format(comparar(gen5, gen1)) + '{:>15}'.format(
    comparar(gen5, gen2)) + '{:>15}'.format(comparar(gen5, gen3)) + '{:>15}'.format(
    comparar(gen5, gen4)) + '{:>15}'.format(comparar(gen5, gen5)))
