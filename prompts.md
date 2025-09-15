# Prompt One

showcase
<img width="1889" height="933" alt="image" src="https://github.com/user-attachments/assets/d7388f4f-cc6d-4c72-9c79-d03ae677792b" />
prompt:

use design.json as design reference:
{
  "design_system": {
    "colors": {
      "primary": "#000000",
      "secondary": ["#FFEB3B", "#C5E86C", "#8FC8F0"],
      "accent": "#F0F0F0",
      "background": "#FFFFFF",
      "text_primary": "#000000",
      "text_secondary": "#555555",
      "border": "#E5E5E5",
      "highlight": "#F9F9F9"
    },
    "typography": {
      "font_family": "Inter, sans-serif",
      "font_weights": {
        "light": 300,
        "regular": 400,
        "medium": 500,
        "bold": 700
      },
      "sizes": {
        "heading_large": "32px",
        "heading_medium": "24px",
        "body": "16px",
        "small": "14px"
      },
      "line_height": {
        "heading": 1.2,
        "body": 1.5
      }
    },
    "spacing": {
      "padding": {
        "small": "8px",
        "medium": "16px",
        "large": "32px"
      },
      "margin": {
        "small": "8px",
        "medium": "16px",
        "large": "32px"
      },
      "gap": {
        "small": "8px",
        "medium": "16px",
        "large": "24px"
      }
    },
    "layout": {
      "container": {
        "max_width": "1200px",
        "margin": "0 auto",
        "padding": "16px"
      },
      "grid": {
        "columns": 12,
        "gap": "16px"
      },
      "sidebar": {
        "width": "280px",
        "background": "#F9F9F9",
        "padding": "16px",
        "position": "fixed",
        "height": "100vh"
      },
      "main_content": {
        "margin_left": "300px",
        "padding": "24px"
      }
    },
    "components": {
      "button": {
        "primary": {
          "background": "#FFEB3B",
          "text_color": "#000000",
          "border_radius": "8px",
          "padding": "12px 24px"
        },
        "secondary": {
          "background": "#FFFFFF",
          "text_color": "#000000",
          "border": "1px solid #E5E5E5",
          "border_radius": "8px",
          "padding": "12px 24px"
        }
      },
      "input": {
        "background": "#FFFFFF",
        "border": "1px solid #E5E5E5",
        "border_radius": "8px",
        "padding": "12px",
        "placeholder_color": "#AAAAAA"
      },
      "cards": {
        "background": "#FFFFFF",
        "shadow": "0 2px 8px rgba(0,0,0,0.05)",
        "border_radius": "12px",
        "padding": "16px"
      },
      "modals": {
        "background": "#FFFFFF",
        "shadow": "0 4px 16px rgba(0,0,0,0.1)",
        "border_radius": "12px",
        "padding": "24px"
      },
      "icons": {
        "size": "20px",
        "color": "#555555"
      }
    },
    "ui_patterns": {
      "sidebar_navigation": {
        "vertical_list": true,
        "icons_with_text": true,
        "highlight_active": true
      },
      "cards_and_panels": {
        "rounded_corners": true,
        "shadow": true,
        "spacing_consistency": true
      },
      "typography_hierarchy": {
        "bold_headings": true,
        "subtle_body_text": true,
        "color_accents_for_emphasis": true
      },
      "button_styles": {
        "primary_and_secondary_variants": true,
        "hover_effects": true,
        "rounded_corners": true
      },
      "feedback_messages": {
        "highlight_box": true,
        "subtle_background_color": true
      }
    },
    "interaction": {
      "hover_effects": {
        "buttons": "slight background darken",
        "cards": "lift shadow",
        "links": "underline or color change"
      },
      "focus_states": {
        "inputs": "border color change",
        "buttons": "slight shadow increase"
      }
    }
  }
}
