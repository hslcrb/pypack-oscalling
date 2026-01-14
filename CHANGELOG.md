# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2026-01-15

### Added
- **Modern Build System**: Migrated from `setup.py` to `pyproject.toml` (PEP 517/518)
- **Full Type Hints**: Added comprehensive type annotations to all modules
- **Enhanced Documentation**: Complete docstrings for every class and method
- **Better Error Handling**: Improved exception handling and error messages across all managers
- **API Documentation**: Comprehensive API overview in README

### Changed
- **FileSystemManager**: Added robust error handling and type safety
- **MemoryManager**: Improved exception handling for process info retrieval
- **HardwareManager**: Added fallback values for disk operations
- **ProcessManager**: Enhanced error reporting for command execution
- **EnvManager**: Improved type hints and documentation

### Fixed
- Atomic write operations now handle edge cases better
- Process termination now handles access denied gracefully
- Directory creation now properly handles parent directories

## [1.0.0] - 2026-01-15

### Added
- Initial release of oscalling
- FileSystemManager for enhanced file operations
- MemoryManager for memory monitoring and optimization
- HardwareManager for CPU, RAM, and Disk monitoring
- EnvManager for environment variable management
- ProcessManager for command execution and process control
- SystemManager as central hub for all operations
