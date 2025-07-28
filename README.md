# Whiteboard

WBS Chart Creator MVP - A React-based whiteboard application for creating Work Breakdown Structure charts.

## Development

This project is built with React and Vite, providing fast development and hot module replacement.

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build
- `npm run test` - Run tests with Vitest
- `npm run test:coverage` - Run tests with coverage

### Dependencies

- **React 19.1.0** - UI framework
- **ReactFlow 11.11.4** - Flow chart and diagram library
- **Zustand 5.0.6** - State management

### Getting Started

1. Install dependencies: `npm install`
2. Start development server: `npm run dev`
3. Open http://localhost:5173 in your browser

## Testing

This project uses [Vitest](https://vitest.dev/) and [React Testing Library](https://testing-library.com/docs/react-testing-library/) for unit and component testing.

### Install dependencies

```bash
npm install --save-dev vitest @testing-library/react @testing-library/jest-dom
```

### Running tests

- `npm run test` to start Vitest in watch mode.
- `npm run test:coverage` to run tests once and generate a coverage report.
