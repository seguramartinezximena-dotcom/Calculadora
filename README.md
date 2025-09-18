# Calculadora
calculadora de python
import flet as ft
import math


def main(page: ft.Page):
    page.title="Calculadora Simple"
    page.bgcolor=ft.Colors.PURPLE_ACCENT_400

    titulo=ft.Text(
        "🧧 Calculadora Basica",
        size=28,
        text_align="center",
        weight="bold"
    )

    num1=ft.TextField(
        label="Numero 1",
        width=200,
        text_style=ft.TextStyle(color=ft.colors.GREEN)
    )

    num2=ft.TextField(
        label="Numero 2",
        width=200,
        text_style=ft.TextStyle(color=ft.colors.GREEN)
    )

    resultado=ft.Text(
        value="Resultado",
        size=20,
        color=ft.Colors.GREEN,
        text_align="center"
    )
