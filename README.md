# SQLite-Management-Studio

A simple, lightweight, user-friendly tool with an interface similar to SQL Server Management Studio (SSMS) for ease of use. Manage SQLite databases effortlessly with an intuitive Windows desktop GUI.

## ✨ Features

- **Visual Database Explorer**: Browse databases, tables, views, indexes, and triggers like in SSMS
- **SQL Query Editor**: Syntax-highlighted editor with IntelliSense, execution, and result grids
- **Table Designer**: Create and modify tables with a visual designer interface
- **Data Editor**: Inline editing for table data with filtering, sorting, and searching
- **Export/Import**: Export query results or data to CSV, JSON, Excel; import from CSV
- **Schema Compare**: Compare database schemas side-by-side
- **Script Generation**: Generate CREATE/ALTER scripts for database objects
- **Backup/Restore**: One-click database backup and restore functionality
- **Lightweight & Fast**: Native Windows performance optimized for SQLite files

## 🛠️ Tech Stack

- **Framework**: WPF (.NET 6.0 / .NET Framework 4.8)
- **Database**: System.Data.SQLite (native SQLite integration)
- **UI/UX**: XAML with Material Design in XAML Toolkit
- **MVVM**: CommunityToolkit.Mvvm for clean architecture
- **Syntax Highlighting**: AvalonEdit or ICSharpCode.AvalonEdit
- **Platform**: Windows 10/11 (x64)

## 🚀 Quick Start

### Prerequisites
- Windows 10 (version 1809+) or Windows 11
- .NET 8.0 Desktop Runtime (x64)

### Download & Install
1. Download the latest release from [Releases](https://github.com/yourusername/SQLite-Management-Studio/releases)
2. Run `SQLiteManagementStudioSetup.msi` as Administrator
3. Launch from Start Menu

### Portable Version
Download `SQLiteManagementStudio-Portable.zip`, extract, and run `SQLiteManagementStudio.exe`

## 📋 System Requirements

| Requirement | Minimum | Recommended |
|-------------|---------|-------------|
| OS | Windows 10 1809 | Windows 11 |
| CPU | 1 GHz | Intel i5+ |
| RAM | 4 GB | 8 GB+ |
| Storage | 100 MB | 500 MB |

## 🔌 Usage Guide

1. **Launch** the application
2. **Connect**: File → Open Database → Select `.db` / `.sqlite` / `.db3` file
3. **Explore**: Use Object Explorer (View → Object Explorer or `Ctrl+R`)
4. **Query**: New Query (`Ctrl+N`), write SQL, execute (`F5` or `Ctrl+E`)
5. **Manage Data**: Right-click tables → Edit Top 200 Rows

**SSMS Keyboard Shortcuts**:
- `Ctrl+N` - New Query Window
- `F5` - Execute Current Query
- `Ctrl+R` - Toggle Object Explorer
- `Ctrl+S` - Save Changes
- `Ctrl+F` - Find/Replace
- `Alt+F1` - Object Properties

## 📁 File Locations

