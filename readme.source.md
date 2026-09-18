```aura width=800 height=360
<div
  style={{
    width: '800px',
    height: '360px',
    position: 'relative',
    display: 'flex',
    overflow: 'hidden',
    background: '#100e0b',
    fontFamily: 'sans-serif',
    border: '1px solid rgba(179,229,255,0.35)',
    borderRadius: '24px',
    boxSizing: 'border-box'
  }}
>
  <svg
    width="800"
    height="360"
    viewBox="0 0 800 360"
    xmlns="http://www.w3.org/2000/svg"
    style={{
      position: 'absolute',
      left: '0px',
      top: '0px',
      width: '800px',
      height: '360px',
      pointerEvents: 'none'
    }}
    aria-hidden="true"
  >
    <defs>
      <filter
        id="beamBlur"
        x="-200"
        y="-200"
        width="1200"
        height="760"
      >
        <feGaussianBlur stdDeviation="14" />
      </filter>

      <filter
        id="beamSoftBlur"
        x="-150"
        y="-150"
        width="1100"
        height="660"
      >
        <feGaussianBlur stdDeviation="7" />
      </filter>
    </defs>

    <g
      filter="url(#beamBlur)"
      opacity="0.8"
    >
      <polygon
        points="-80,520 -25,520 475,-160 420,-160"
        fill="#2563eb"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-1400 0; 1400 0"
          dur="5s"
          repeatCount="indefinite"
        />
      </polygon>

      <polygon
        points="-140,520 -105,520 395,-160 360,-160"
        fill="#b3e5ff"
        opacity="0.75"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-1700 0; 1400 0"
          dur="6.5s"
          repeatCount="indefinite"
        />
      </polygon>

      <polygon
        points="-220,520 -175,520 325,-160 280,-160"
        fill="#143c78"
        opacity="0.9"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-1900 0; 1500 0"
          dur="8s"
          repeatCount="indefinite"
        />
      </polygon>

      <polygon
        points="-300,520 -265,520 235,-160 200,-160"
        fill="#2563eb"
        opacity="0.7"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-2100 0; 1500 0"
          dur="7s"
          repeatCount="indefinite"
        />
      </polygon>

      <polygon
        points="-400,520 -350,520 150,-160 100,-160"
        fill="#b3e5ff"
        opacity="0.6"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-2300 0; 1500 0"
          dur="9s"
          repeatCount="indefinite"
        />
      </polygon>
    </g>

    <g
      filter="url(#beamSoftBlur)"
      opacity="0.9"
    >
      <polygon
        points="-50,520 -35,520 465,-160 450,-160"
        fill="#b3e5ff"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-1200 0; 1500 0"
          dur="4.5s"
          repeatCount="indefinite"
        />
      </polygon>

      <polygon
        points="-180,520 -165,520 335,-160 320,-160"
        fill="#2563eb"
        opacity="0.9"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-1600 0; 1500 0"
          dur="5.8s"
          repeatCount="indefinite"
        />
      </polygon>

      <polygon
        points="-330,520 -315,520 185,-160 170,-160"
        fill="#b3e5ff"
        opacity="0.7"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-2000 0; 1500 0"
          dur="7.2s"
          repeatCount="indefinite"
        />
      </polygon>

      <polygon
        points="-500,520 -485,520 15,-160 0,-160"
        fill="#2563eb"
        opacity="0.65"
      >
        <animateTransform
          attributeName="transform"
          type="translate"
          values="-2400 0; 1500 0"
          dur="8.5s"
          repeatCount="indefinite"
        />
      </polygon>
    </g>
  </svg>

  <div
    style={{
      position: 'relative',
      width: '800px',
      height: '360px',
      display: 'flex',
      flexDirection: 'column',
      alignItems: 'center',
      justifyContent: 'center'
    }}
  >
    <div
      style={{
        display: 'flex',
        flexDirection: 'column',
        alignItems: 'center',
        justifyContent: 'center'
      }}
    >
      <div
        style={{
          display: 'flex',
          fontSize: '42px',
          fontWeight: '700',
          lineHeight: '50px',
          color: '#d9f3ff',
          letterSpacing: '1px'
        }}
      >
        {(github && github.user && (github.user.name || github.user.login)) || 'GitHub Developer'}
      </div>

      <div
        style={{
          display: 'flex',
          marginTop: '10px',
          fontSize: '16px',
          lineHeight: '22px',
          color: '#b3e5ff',
          letterSpacing: '4px'
        }}
      >
        Linux enjoyer
      </div>

      <div
        style={{
          display: 'flex',
          flexDirection: 'row',
          alignItems: 'center',
          justifyContent: 'center',
          marginTop: '28px'
        }}
      >
        <div
          style={{
            display: 'flex',
            padding: '8px 14px',
            marginRight: '10px',
            border: '1px solid rgba(179,229,255,0.35)',
            borderRadius: '20px',
            color: '#d9f3ff',
            fontSize: '12px',
            lineHeight: '16px',
            background: 'rgba(4,16,34,0.55)'
          }}
        >
          python
        </div>

        <div
          style={{
            display: 'flex',
            padding: '8px 14px',
            marginRight: '10px',
            border: '1px solid rgba(179,229,255,0.35)',
            borderRadius: '20px',
            color: '#d9f3ff',
            fontSize: '12px',
            lineHeight: '16px',
            background: 'rgba(4,16,34,0.55)'
          }}
        >
          shell
        </div>

        <div
          style={{
            display: 'flex',
            padding: '8px 14px',
            border: '1px solid rgba(179,229,255,0.35)',
            borderRadius: '20px',
            color: '#d9f3ff',
            fontSize: '12px',
            lineHeight: '16px',
            background: 'rgba(4,16,34,0.55)'
          }}
        >
          linux
        </div>
      </div>
    </div>
  </div>
</div>
```
