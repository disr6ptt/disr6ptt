```aura width=800 height=200
<div style={{
  display: 'flex',
  flexDirection: 'column',
  alignItems: 'center',
  justifyContent: 'center',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(135deg, #1e1e2e 0%, #181825 60%, #11111b 100%)',
  borderRadius: '16px',
  border: '1px solid #313244',
  gap: '18px',
  position: 'relative',
  overflow: 'hidden',
}}>
  <div style={{
    display: 'flex',
    position: 'absolute',
    top: '0',
    left: '0',
    right: '0',
    height: '3px',
    background: 'linear-gradient(90deg, #89b4fa 0%, #cba6f7 50%, #f38ba8 100%)',
  }} />

  <div style={{
    display: 'flex',
    position: 'absolute',
    top: '-60px',
    right: '-60px',
    width: '200px',
    height: '200px',
    borderRadius: '50%',
    background: 'radial-gradient(circle, rgba(137,180,250,0.08) 0%, transparent 70%)',
  }} />

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: '20px',
  }}>
    <div style={{
      display: 'flex',
      width: '76px',
      height: '76px',
      borderRadius: '50%',
      background: 'linear-gradient(135deg, #89b4fa, #cba6f7, #f38ba8)',
      alignItems: 'center',
      justifyContent: 'center',
    }}>
      <div style={{
        display: 'flex',
        width: '70px',
        height: '70px',
        borderRadius: '50%',
        overflow: 'hidden',
        border: '2px solid #1e1e2e',
      }}>
        <img
          src="https://github.com/disr6ptt.png"
          style={{
            width: '70px',
            height: '70px',
          }}
        />
      </div>
    </div>

    <div style={{ display: 'flex', flexDirection: 'column', gap: '5px' }}>
      <span style={{
        fontSize: '38px',
        fontWeight: '700',
        color: '#cdd6f4',
        letterSpacing: '-1px',
      }}>
      disr6pt
      </span>
      <span style={{
        fontSize: '14px',
        color: '#89b4fa',
        fontWeight: '500',
        letterSpacing: '1.5px',
        textTransform: 'uppercase',
      }}>
        linux enthusiast · productivity · ricing
      </span>
    </div>
  </div>

  <div style={{ display: 'flex', gap: '8px' }}>
    {[
      { tag: 'python', bg: 'rgba(255,255,220,0.12)', border: '#d62828', color: '#d62828' },
      { tag: 'qml',    bg: 'rgba(255,255,220,0.12)', border: '#69A481', color: '#69A481' },
      { tag: 'shell',  bg: 'rgba(255,255,220,0.12)', border: '#ff6f3c', color: '#ff6f3c' },
      { tag: 'linux',  bg: 'rgba(255,255,220,0.12)', border: '#2ec4b6', color: '#2ec4b6' },
    ].map(({ tag, bg, border, color }) => (
      <div key={tag} style={{
        display: 'flex',
        padding: '4px 14px',
        borderRadius: '999px',
        background: bg,
        border: `1px solid ${border}`,
        color: color,
        fontSize: '12px',
        fontWeight: '700',
        letterSpacing: '0.8px',
        textTransform: 'uppercase',
      }}>
        {tag}
      </div>
    ))}
  </div>
</div>
```
