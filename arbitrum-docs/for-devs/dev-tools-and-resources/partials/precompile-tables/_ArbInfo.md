<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Solidity interface</th>
      <th>Go implementation</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>getBalance(address account)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/b16bf0b737468382854dac28346fec8b65b55989/src/precompiles/ArbInfo.sol#L11"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.1.3/precompiles/ArbInfo.go#L17"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>GetBalance retrieves an account's balance</td>
    </tr>
    <tr>
      <td>
        <code>getCode(address account)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/b16bf0b737468382854dac28346fec8b65b55989/src/precompiles/ArbInfo.sol#L14"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.1.3/precompiles/ArbInfo.go#L25"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>GetCode retrieves a contract's deployed code</td>
    </tr>
  </tbody>
</table>