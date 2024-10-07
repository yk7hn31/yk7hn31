## `yk7hn31-beta-v1.yang`

```yang
module my-profile {
  namespace "https://github.com/yk7hn31";
  prefix user;

  container profile {
    leaf name {
      type string;
      default "Lucas Han";
    }
    leaf occupation {
      type string;
      default "High-Schooler";
    }

    container tech-stack {
      leaf-list language {
        type string;
        default ["JavaScript", "Python", "TypeScript", "Swift"];
      }
      leaf-list framework {
        type string;
        default ["React", "Node.js", "Express", "Deno"];
      }
      leaf-list tools {
        type string;
        default ["Git", "Docker"];
      }
      leaf-list database {
        type string;
        default ["MySQL", "MongoDB"];
      }
    }

    leaf motto {
      type string;
      default "Always in beta, always improving.";
    }

    leaf-list languages {
      type string;
      default ["English 🇺🇸", "Japanese 🇯🇵" "Korean 🇰🇷"];
    }
  }
}
```
