# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository manages a 12-month New Zealand IT job search process. The project focuses on systematic job hunting through data-driven analysis and document automation.

## Core Functions

- **Job Analysis**: Analyze IT job postings and market trends in New Zealand
- **Resume Customization**: Tailor resumes for specific job applications
- **Cover Letter Generation**: Create targeted cover letters
- **Market Research**: Track and analyze the NZ IT job market

## File Organization

The project primarily uses Markdown files for documentation and data storage. Content should be organized to support the 12-month job search timeline and facilitate easy retrieval and analysis.

## Specialized Agents

The project includes four specialized agents in `.claude/agents/`. When using the Task tool, utilize these specific agent types:

- `nz-it-job-analyzer`: Analyzes IT job postings with senior hiring manager expertise (20+ years NZ IT experience). Provides comprehensive job analysis including technical requirements, cultural fit assessment, salary research, and resume evaluation frameworks specific to the NZ market.

- `resume-optimizer`: Customizes and optimizes resumes for specific IT job applications in the New Zealand market. Includes ATS optimization, technical skill presentation, achievement quantification, and NZ employment market conventions.

- `cover-letter-writer`: Creates targeted cover letters for NZ IT roles. Balances professionalism with personality, addresses specific job requirements, and demonstrates company research and cultural understanding.

- `nz-it-market-researcher`: Provides comprehensive analysis of the New Zealand IT job market including salary benchmarks, skill demand trends, industry insights, and employment patterns across different regions and sectors.

## Project Structure

The repository contains:

- `.claude/agents/`: Four specialized agents for NZ IT job search tasks
- `CLAUDE.md`: This guidance file for future Claude Code instances

Content should be organized around:
- Job application tracking and analysis
- Resume versions and customizations
- Cover letter templates and variations
- Market research data and insights
- Progress tracking over the 12-month period

## Workflow

Standard Git workflow on the `main` branch. Focus on maintaining organized documentation that supports systematic job search activities and data-driven decision making.