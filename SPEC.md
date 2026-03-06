# Asimetrix Sales Deck - Flip Cards

## Project Overview
- **Project name**: Asimetrix Sales Deck
- **Type**: Webapp interactiva (NextJS)
- **Core functionality**: Deck de flip cards para que comerciales respondan objeciones de clientes sobre productos Asimetrix
- **Target users**: Equipo comercial de Asimetrix

## UI/UX Specification

### Layout Structure
- **Header**: Logo Asimetrix + título del deck
- **Main**: Grid de flip cards con efecto 3D
- **Navigation**: Controles para navegar entre categorías de preguntas

### Responsive Breakpoints
- Mobile: < 768px (1 columna)
- Tablet: 768px - 1024px (2 columnas)
- Desktop: > 1024px (3-4 columnas)

### Visual Design

#### Color Palette
- **Primary**: `#0A1628` (azul oscuro institucional)
- **Secondary**: `#1E3A5F` (azul medio)
- **Accent**: `#00D4AA` (turquesa brillante)
- **Text Primary**: `#FFFFFF`
- **Text Secondary**: `#94A3B8`
- **Card Front**: `#0F2744` (fondo tarjetas)
- **Card Back**: `#1A3A5C` (reverso con gradiente)

#### Typography
- **Font Family**: "DM Sans" (headings), "Inter" (body)
- **Headings**: 32px bold
- **Card Title**: 20px semibold
- **Card Body**: 16px regular

#### Visual Effects
- Flip card con `transform: rotateY(180deg)` y `perspective: 1000px`
- Transición suave de 0.6s
- Hover con sutil lift effect
- Gradiente en reverso de tarjetas

### Components

#### FlipCard
- **Front**: Pregunta del cliente en texto prominente
- **Back**: Respuesta comercial con iconos
- **States**: default, hover (lift), flipped (rotated)
- **Click**: Alterna entre anverso y reverso

#### CategoryFilter
- Botones para filtrar por tipo de pregunta
- Categories: "Todas", "Precio", "Producto", "Tiempo", "Competencia"

#### ProgressIndicator
- Muestra cuántas tarjetas quedan por ver

## Functionality Specification

### Core Features
1. Flip card interactivo con click para voltear
2. Navegación por categorías de objeciones
3. Contador de tarjetas vistas
4. Diseño responsive

### Content (Dummy)
Categorías de preguntas:
1. **Precio**: "¿Es muy caro?", "¿Hay descuento?"
2. **Producto**: "¿Qué incluye?", "¿Es difícil de usar?"
3. **Tiempo**: "¿Cuánto tarda en implementarse?"
4. **Competencia": "¿Por qué no mejor X competencia?"

## Acceptance Criteria
- [ ] Flip cards funcionan con click
- [ ] Transición 3D suave
- [ ] Responsive en todos los breakpoints
- [ ] Contenido dummy visible
- [ ] Navegación por categorías funciona
