function Sumar {
    param (
        [float]$num1,
        [float]$num2
    )
    $resultado = $num1 + $num2
    Write-Host "Resultado: $resultado"
}

function Restar {
    param (
        [float]$num1,
        [float]$num2
    )
    $resultado = $num1 - $num2
    Write-Host "Resultado: $resultado"
}

function Multiplicar {
    param (
        [float]$num1,
        [float]$num2
    )
    $resultado = $num1 * $num2
    Write-Host "Resultado: $resultado"
}

function Dividir {
    param (
        [float]$num1,
        [float]$num2
    )
    if ($num2 -eq 0) {
        Write-Host "No se puede dividir por cero."
    } else {
        $resultado = $num1 / $num2
        Write-Host "Resultado: $resultado"
    }
}

Write-Host "Calculadora en PowerShell"
Write-Host "Opciones:"
Write-Host "1. Sumar"
Write-Host "2. Restar"
Write-Host "3. Multiplicar"
Write-Host "4. Dividir"

$opcion = Read-Host "Seleccione una opción (1/2/3/4)"

if ($opcion -eq "1") {
    $num1 = Read-Host "Ingrese el primer número"
    $num2 = Read-Host "Ingrese el segundo número"
    Sumar $num1 $num2
} elseif ($opcion -eq "2") {
    $num1 = Read-Host "Ingrese el primer número"
    $num2 = Read-Host "Ingrese el segundo número"
    Restar $num1 $num2
} elseif ($opcion -eq "3") {
    $num1 = Read-Host "Ingrese el primer número"
    $num2 = Read-Host "Ingrese el segundo número"
    Multiplicar $num1 $num2
} elseif ($opcion -eq "4") {
    $num1 = Read-Host "Ingrese el numerador"
    $num2 = Read-Host "Ingrese el denominador"
    Dividir $num1 $num2
} else {
    Write-Host "Opción no válida."
}
