# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Go-based resume API project. The repository is currently in early setup phase with basic structure files.

## Development Commands

Since this is a new Go project, standard Go commands will be used:

- `go mod init github.com/charlestakang/projects/resume_api_golang` - Initialize Go module (if not done)
- `go build` - Build the application
- `go run .` - Run the application
- `go test ./...` - Run all tests
- `go test -v ./...` - Run tests with verbose output
- `go test -race ./...` - Run tests with race condition detection
- `go mod tidy` - Clean up module dependencies
- `go fmt ./...` - Format Go code
- `go vet ./...` - Run Go vet for static analysis

## Repository Structure

The repository currently contains:
- Basic Go .gitignore with standard exclusions
- Empty README.md
- MIT License

The project structure will likely follow standard Go project layout conventions once development begins.