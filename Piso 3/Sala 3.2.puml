@startuml
loop mientras ambos sigan vivos
  Arena -> Guerrero : atacar()
  alt mana >= 20
    Arena -> Mago : lanzarHechizo()
  else sin mana
    Arena -> Mago : ataqueBasico()
  end
end
@enduml
