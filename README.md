<style>
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.6;
        color: var(--text-color);
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
        background-color: #f9f9f9;
    }
    
    h2 {
        color: var(--primary-color);
        padding-bottom: 8px;
        border-bottom: 2px solid var(--accent-color);
        margin-top: 30px;
    }
    
    h3 {
        color: var(--secondary-color);
        margin: 20px 0 10px 0;
        font-weight: 500;
    }
    
    .weeks-container {
        display: flex;
        gap: 30px;
        flex-wrap: wrap;
    }
    
    .week {
        flex: 1;
        min-width: 300px;
        background: white;
        padding: 20px;
        border-radius: var(--border-radius);
        box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    
    .subtasks {
        margin-left: 10px;
    }
    
    .subtasks div {
        padding: 6px 0;
        border-bottom: 1px dotted #eee;
    }
    
    .subtasks div:last-child {
        border-bottom: none;
    }
    
    a {
        color: var(--accent-color);
        text-decoration: none;
        transition: color 0.2s;
    }
    
    a:hover {
        color: var(--primary-color);
        text-decoration: underline;
    }
    
    @media (max-width: 768px) {
        .weeks-container {
            flex-direction: column;
            gap: 20px;
        }
        
        .week {
            min-width: auto;
        }
    }
</style>
