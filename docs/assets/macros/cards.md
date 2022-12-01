{% macro start_grid(columns=3) -%}
<div class="nt-cards nt-grid cols-{{ columns }}">
{%- endmacro %}

{% macro add_card(title='', content='', image='', url='') -%}
<div>
    <div class="nt-card">
        {% if url != '' %}
            <a href="{{ url }}" title="{{ title | e }}">
        {% endif  %}
        {% if image != '' %}
            <div class="nt-card-image tags">
                <img src="{{ image }}" class="skip-lightbox">
            </div>
        {% endif %}
        <div class="nt-card-content">
            <p class="nt-card-title">{{ title }} </p>
        </div>
        <p class="nt-card-text">{{ content }}</p>
        {% if url != '' %}
            </a>
        {% endif %}
    </div>
</div>
{%- endmacro %}

{% macro end_grid() -%}
</div>
{%- endmacro %}
