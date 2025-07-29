# Awesome Claude Agents - AI Development Team 🚀

**Supercharge Claude Code with a team of specialized AI agents** that work together to build complete features, debug complex issues, and handle any technology stack with expert-level knowledge.

## 🎯 The Problem & Solution

While Claude Code is powerful, complex projects need specialized expertise. Generic AI responses often miss framework-specific best practices, leading to suboptimal code.

**Our solution:** A team of specialized AI agents that work together, each with deep expertise in their domain. Just like a real development team, but available 24/7.

## 💡 See The Difference

```
You: "Build user management"

Without Agent Team:
Claude: *Generic authentication implementation*

With Agent Team:
├── Tech Lead: "I'll coordinate this for your Laravel + React project"
├── Laravel Expert: "Implementing Sanctum auth with role-based permissions"
├── API Architect: "Designing RESTful resources with proper validation"
├── Frontend Dev: "Building React components with hooks and context"
└── Database Expert: "Optimizing Eloquent relationships and indexes"

Result: Production-ready, framework-specific, best-practice implementation
```

## 🚀 Quick Start (2 Minutes)

### 1. Install the Agents
```bash
git clone https://github.com/bootstrapguru/awesome-claude-agents.git
cp -r awesome-claude-agents/agents ~/.claude/
```

### 2. Configure for Your Project
Let Claude analyze your project and set up the perfect team:

```bash
claude "Analyze project, detect tech stack, configure CLAUDE.md with optimal agents and routing rules from ~/.claude/agents/. Map tasks to specialists: API endpoints, frontend components, database queries, performance optimization. Use framework-specific agents when available, universal fallbacks otherwise."
```

### 3. Start Building
```bash
claude "Build a complete user authentication system"
```

Your AI team will automatically use the right specialists for your tech stack!

## 🎯 How Auto-Configuration Works

When you run the configuration command, Claude will:

1. **Analyze Your Project** - Detects frameworks, languages, and patterns
2. **Select Your Team** - Assigns specialists based on your tech stack
3. **Create Workflows** - Sets up intelligent routing for common tasks
4. **Configure CLAUDE.md** - Saves your team configuration

Example configurations:

**Laravel + React Project:**
```markdown
# Your AI Development Team

Tech Stack: Laravel 10, React 18, MySQL, Redis

Agent Assignments:
- API tasks → @laravel-api-architect
- Backend logic → @laravel-backend-expert  
- Frontend → @frontend-developer
- Database → @laravel-eloquent-expert
- Performance → @performance-optimizer

Your specialized team is ready!
```

**.NET + TypeScript Project:**
```markdown
# Your AI Development Team

Tech Stack: .NET 9, TypeScript 5.7, SQL Server, Vite

Agent Assignments:
- Solution architecture → @dotnet-solution-architect
- API development → @dotnet-core-architect
- Data layer → @efcore-expert
- Frontend → @modern-frontend-architect
- Database → @sqlserver-expert
- Build optimization → @vite-expert

Your enterprise team is configured!
```

## 👥 Meet Your AI Development Team

### 🎭 Leadership
- **[Tech Lead Orchestrator](agents/orchestrators/tech-lead-orchestrator.md)** - Understands vague requirements, breaks down complex tasks, coordinates specialists
- **[Project Analyst](agents/orchestrators/project-analyst.md)** - Deep understanding of your codebase structure and patterns
- **[.NET Solution Architect](agents/orchestrators/dotnet-solution-architect.md)** - Enterprise .NET solutions, microservices, cloud architecture
- **[Modern Frontend Architect](agents/orchestrators/modern-frontend-architect.md)** - Cross-platform web/mobile, micro-frontends, performance

### 💼 Backend Specialists
- **[Laravel Backend Expert](agents/specialized/laravel/laravel-backend-expert.md)** - Laravel patterns, Eloquent ORM, queues, events
- **[Laravel API Architect](agents/specialized/laravel/laravel-api-architect.md)** - RESTful APIs, resources, Sanctum auth
- **[.NET Framework Migration Expert](agents/specialized/dotnet/dotnet-framework-migration-expert.md)** - .NET Framework 4.8 to .NET 9+ migration specialist
- **[.NET Core Architect](agents/specialized/dotnet/dotnet-core-architect.md)** - .NET 9+, minimal APIs, microservices, cloud-native
- **[EF Core Expert](agents/specialized/dotnet/efcore-expert.md)** - Entity Framework Core 9+, data access patterns, performance
- **[Universal Backend Developer](agents/universal/backend-developer.md)** - Polyglot programmer for any backend language

### 🗄️ Database Specialists
- **[SQL Server Expert](agents/specialized/database/sqlserver-expert.md)** - T-SQL optimization, indexes, stored procedures, Always On
- **[PostgreSQL Expert](agents/specialized/database/postgresql-expert.md)** - JSONB, full-text search, partitioning, performance tuning

### 🎨 Frontend Specialists
- **[Frontend Developer](agents/universal/frontend-developer.md)** - React, Vue, Angular expertise with modern patterns
- **[TypeScript Architect](agents/specialized/typescript/typescript-architect.md)** - TypeScript 5.7+, advanced type systems, domain modeling
- **[shadcn/ui Expert](agents/specialized/typescript/shadcn-ui-expert.md)** - Modern React components, Radix UI, Tailwind integration
- **[Tailwind CSS Expert](agents/universal/tailwind-css-expert.md)** - Pixel-perfect responsive designs

### 🗺️ Mapping & Visualization
- **[Mapbox Expert](agents/specialized/mapping/mapbox-expert.md)** - Mapbox GL JS v3, real-time tracking, 3D terrain, custom styles

### ☁️ Platform Specialists
- **[Supabase Fullstack Expert](agents/specialized/supabase/supabase-fullstack-expert.md)** - PostgreSQL, Auth, Storage, Edge Functions, Realtime, Vector embeddings

### 🛠️ Build Tools & DevOps
- **[Vite Expert](agents/specialized/build/vite-expert.md)** - Vite 6+, build optimization, plugin development, HMR
- **[Webpack Migration Expert](agents/specialized/build/webpack-migration-expert.md)** - Webpack to Vite migration, configuration conversion

### 🔧 Code Quality Team
- **[Code Archaeologist](agents/core/code-archaeologist.md)** - Understands and documents any codebase
- **[Code Reviewer](agents/core/code-reviewer.md)** - Ensures best practices and standards
- **[Performance Optimizer](agents/core/performance-optimizer.md)** - Makes everything blazing fast

[Browse all agents →](agents/)

## 🎬 Real-World Examples

### Building a SaaS Dashboard
```
You: "I need a dashboard for my SaaS with user analytics"

What happens:
→ Tech Lead breaks down requirements
→ Backend Expert creates analytics aggregation service
→ API Architect designs efficient data endpoints  
→ Frontend Dev builds interactive charts with React
→ Performance Expert implements Redis caching

Result: Complete, scalable dashboard following best practices
```

### Adding Real-Time Features
```
You: "Add real-time notifications to my app"

Team collaboration:
→ Backend Expert implements WebSocket server with Laravel Echo
→ Frontend Dev creates notification components with real-time updates
→ Database Expert designs efficient message storage
→ Performance Expert ensures proper scaling

Result: Production-ready real-time system
```

### Debugging Complex Issues
```
You: "Users are complaining the app is slow"

Investigation process:
→ Performance Expert profiles your application
→ Database Expert identifies N+1 query problems
→ Backend Expert implements eager loading
→ Frontend Dev adds proper loading states
→ Caching Expert implements strategic caching

Result: 10x performance improvement with detailed optimization report
```

## 🔥 Why Teams Beat Solo AI

### 🧠 Specialized Expertise
Each agent has deep knowledge in their domain. Your Laravel expert knows Eloquent inside-out, while your React specialist breathes hooks and context.

### 👥 Real Collaboration
Agents work together, handing off tasks and sharing context. The API architect coordinates with both backend and frontend specialists.

### 🎯 Framework-Specific Solutions
No more generic code. Get Laravel service providers, React custom hooks, Django class-based views - whatever matches YOUR stack.

### ⚡ Faster Development
Multiple specialists work in parallel. While one designs your API, another builds your UI components.

## 📈 The Impact

- **Ship 10x Faster** - Complete features in minutes, not days
- **Better Code Quality** - Every line follows framework best practices
- **Learn As You Code** - See how experts approach problems
- **Scale Confidently** - Architecture designed for growth

## 🎯 Perfect For

- **Startups** - Build your MVP at lightning speed with production-ready code
- **Agencies** - Handle any client technology stack with confidence
- **Solo Developers** - Access a full team's expertise whenever you need it
- **Enterprises** - Maintain consistency and best practices across teams
- **.NET Developers** - Modernize legacy systems, build cloud-native microservices
- **Full-Stack Teams** - Coordinate frontend and backend development seamlessly

## 📚 Learn More

- [How Agent Teams Collaborate](docs/agent-team.md) - See the magic behind team coordination
- [Creating Custom Agents](docs/creating-agents.md) - Build specialists for your needs
- [Architecture Guide](docs/architecture.md) - Technical deep dive
- [Best Practices](docs/best-practices.md) - Get the most from your AI team

## 🌈 Coming Soon

- Domain experts (E-commerce, FinTech, HealthTech)
- Mobile development specialists (React Native, Flutter)
- More DevOps team members (Kubernetes, Docker, CI/CD)
- AI/ML specialists (TensorFlow, PyTorch)
- Blockchain developers (Solidity, Web3)

## 💬 Join The Community

- ⭐ **Star this repo** to show support
- 🐛 [Report issues](https://github.com/bootstrapguru/awesome-claude-agents/issues)
- 💡 [Share ideas](https://github.com/bootstrapguru/awesome-claude-agents/discussions)
- 🎉 [Success stories](https://github.com/bootstrapguru/awesome-claude-agents/discussions/categories/show-and-tell)

## 📄 License

MIT License - Use freely in your projects!

---

<p align="center">
  <strong>Transform Claude Code into an AI development team that ships production-ready features</strong><br>
  <em>No configuration. No complexity. Just describe and build.</em>
</p>

<p align="center">
  <a href="https://github.com/bootstrapguru/awesome-claude-agents">GitHub</a> •
  <a href="docs/quick-start.md">Documentation</a> •
  <a href="https://github.com/bootstrapguru/awesome-claude-agents/discussions">Community</a>
</p>