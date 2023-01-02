# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.953 ops/ms
# Warmup Iteration   2: 2.060 ops/ms
# Warmup Iteration   3: 4.075 ops/ms
Iteration   1: 5.012 ops/ms
Iteration   2: 4.960 ops/ms
Iteration   3: 5.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.125 ±(99.9%) 4.428 ops/ms [Average]
  (min, avg, max) = (4.960, 5.125, 5.404), stdev = 0.243
  CI (99.9%): [0.698, 9.553] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.287 ops/ms
# Warmup Iteration   2: 4.189 ops/ms
# Warmup Iteration   3: 5.609 ops/ms
Iteration   1: 5.543 ops/ms
Iteration   2: 5.916 ops/ms
Iteration   3: 5.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.675 ±(99.9%) 3.815 ops/ms [Average]
  (min, avg, max) = (5.543, 5.675, 5.916), stdev = 0.209
  CI (99.9%): [1.860, 9.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.417 ops/ms
# Warmup Iteration   2: 3.950 ops/ms
# Warmup Iteration   3: 5.480 ops/ms
Iteration   1: 5.187 ops/ms
Iteration   2: 5.561 ops/ms
Iteration   3: 5.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.486 ±(99.9%) 4.914 ops/ms [Average]
  (min, avg, max) = (5.187, 5.486, 5.709), stdev = 0.269
  CI (99.9%): [0.572, 10.399] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.366 ops/ms
# Warmup Iteration   2: 3.314 ops/ms
# Warmup Iteration   3: 4.520 ops/ms
Iteration   1: 4.656 ops/ms
Iteration   2: 4.820 ops/ms
Iteration   3: 4.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.751 ±(99.9%) 1.557 ops/ms [Average]
  (min, avg, max) = (4.656, 4.751, 4.820), stdev = 0.085
  CI (99.9%): [3.194, 6.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 22.079 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 7.587 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.319 ±(99.9%) 0.015 ms/op
Iteration   1: 5.982 ±(99.9%) 0.016 ms/op
Iteration   2: 6.636 ±(99.9%) 0.017 ms/op
Iteration   3: 5.999 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.206 ±(99.9%) 6.799 ms/op [Average]
  (min, avg, max) = (5.982, 6.206, 6.636), stdev = 0.373
  CI (99.9%): [≈ 0, 13.005] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 20.627 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 7.174 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.603 ±(99.9%) 0.007 ms/op
Iteration   1: 5.646 ±(99.9%) 0.008 ms/op
Iteration   2: 5.595 ±(99.9%) 0.015 ms/op
Iteration   3: 5.572 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.604 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (5.572, 5.604, 5.646), stdev = 0.038
  CI (99.9%): [4.916, 6.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 21.280 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.404 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.892 ±(99.9%) 0.004 ms/op
Iteration   1: 6.109 ±(99.9%) 0.009 ms/op
Iteration   2: 5.937 ±(99.9%) 0.010 ms/op
Iteration   3: 5.860 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.969 ±(99.9%) 2.322 ms/op [Average]
  (min, avg, max) = (5.860, 5.969, 6.109), stdev = 0.127
  CI (99.9%): [3.647, 8.291] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 23.031 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 8.499 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.786 ±(99.9%) 0.019 ms/op
Iteration   1: 6.996 ±(99.9%) 0.017 ms/op
Iteration   2: 6.798 ±(99.9%) 0.018 ms/op
Iteration   3: 6.991 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.928 ±(99.9%) 2.059 ms/op [Average]
  (min, avg, max) = (6.798, 6.928, 6.996), stdev = 0.113
  CI (99.9%): [4.870, 8.987] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 22.543 ±(99.9%) 0.403 ms/op
# Warmup Iteration   2: 8.916 ±(99.9%) 0.085 ms/op
# Warmup Iteration   3: 6.916 ±(99.9%) 0.036 ms/op
Iteration   1: 5.787 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.892 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   7.971 ms/op
                 createUser·p0.99:   12.141 ms/op
                 createUser·p0.999:  22.153 ms/op
                 createUser·p0.9999: 25.461 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   2: 6.072 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.703 ms/op
                 createUser·p0.50:   5.726 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.928 ms/op
                 createUser·p0.999:  25.510 ms/op
                 createUser·p0.9999: 30.301 ms/op
                 createUser·p1.00:   31.261 ms/op

Iteration   3: 6.091 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.818 ms/op
                 createUser·p0.50:   5.882 ms/op
                 createUser·p0.90:   7.291 ms/op
                 createUser·p0.95:   8.266 ms/op
                 createUser·p0.99:   10.879 ms/op
                 createUser·p0.999:  26.500 ms/op
                 createUser·p0.9999: 30.417 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 160517
  mean =      5.980 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 22194 
    [ 5.000,  7.500) = 125571 
    [ 7.500, 10.000) = 9390 
    [10.000, 12.500) = 2210 
    [12.500, 15.000) = 662 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.703 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      7.225 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     11.679 ms/op
     p(99.9000) =     23.887 ms/op
     p(99.9900) =     30.178 ms/op
     p(99.9990) =     31.201 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 21.307 ±(99.9%) 0.322 ms/op
# Warmup Iteration   2: 6.973 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.845 ±(99.9%) 0.021 ms/op
Iteration   1: 6.019 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   5.718 ms/op
                 existUser·p0.90:   7.291 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   12.426 ms/op
                 existUser·p0.999:  18.940 ms/op
                 existUser·p0.9999: 27.679 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   2: 5.800 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.777 ms/op
                 existUser·p0.50:   5.521 ms/op
                 existUser·p0.90:   7.168 ms/op
                 existUser·p0.95:   8.045 ms/op
                 existUser·p0.99:   10.650 ms/op
                 existUser·p0.999:  24.077 ms/op
                 existUser·p0.9999: 28.635 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 5.700 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   5.407 ms/op
                 existUser·p0.90:   6.857 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   10.679 ms/op
                 existUser·p0.999:  26.214 ms/op
                 existUser·p0.9999: 30.245 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 164391
  mean =      5.837 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 36578 
    [ 5.000,  7.500) = 116367 
    [ 7.500, 10.000) = 8705 
    [10.000, 12.500) = 1754 
    [12.500, 15.000) = 565 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      7.966 ms/op
     p(99.0000) =     11.403 ms/op
     p(99.9000) =     19.766 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     30.936 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.036 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 7.465 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.111 ±(99.9%) 0.027 ms/op
Iteration   1: 6.035 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   3.105 ms/op
                 getUser·p0.50:   5.652 ms/op
                 getUser·p0.90:   7.365 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   11.649 ms/op
                 getUser·p0.999:  18.968 ms/op
                 getUser·p0.9999: 27.974 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   2: 5.902 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.519 ms/op
                 getUser·p0.50:   5.489 ms/op
                 getUser·p0.90:   7.258 ms/op
                 getUser·p0.95:   8.438 ms/op
                 getUser·p0.99:   11.780 ms/op
                 getUser·p0.999:  27.102 ms/op
                 getUser·p0.9999: 31.092 ms/op
                 getUser·p1.00:   32.178 ms/op

Iteration   3: 6.099 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   3.023 ms/op
                 getUser·p0.50:   5.857 ms/op
                 getUser·p0.90:   7.422 ms/op
                 getUser·p0.95:   8.135 ms/op
                 getUser·p0.99:   10.945 ms/op
                 getUser·p0.999:  29.149 ms/op
                 getUser·p0.9999: 32.241 ms/op
                 getUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159649
  mean =      6.011 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 29824 
    [ 5.000,  7.500) = 115933 
    [ 7.500, 10.000) = 10783 
    [10.000, 12.500) = 1951 
    [12.500, 15.000) = 510 
    [15.000, 17.500) = 336 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.519 ms/op
     p(50.0000) =      5.644 ms/op
     p(90.0000) =      7.365 ms/op
     p(95.0000) =      8.307 ms/op
     p(99.0000) =     11.583 ms/op
     p(99.9000) =     24.524 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     32.579 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 23.816 ±(99.9%) 0.434 ms/op
# Warmup Iteration   2: 9.353 ±(99.9%) 0.082 ms/op
# Warmup Iteration   3: 7.053 ±(99.9%) 0.034 ms/op
Iteration   1: 6.950 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.371 ms/op
                 listUser·p0.50:   6.668 ms/op
                 listUser·p0.90:   8.249 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   11.911 ms/op
                 listUser·p0.999:  28.246 ms/op
                 listUser·p0.9999: 31.628 ms/op
                 listUser·p1.00:   32.342 ms/op

Iteration   2: 6.623 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   11.957 ms/op
                 listUser·p0.999:  30.726 ms/op
                 listUser·p0.9999: 33.861 ms/op
                 listUser·p1.00:   39.846 ms/op

Iteration   3: 6.862 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   6.595 ms/op
                 listUser·p0.90:   7.971 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  35.674 ms/op
                 listUser·p0.9999: 37.945 ms/op
                 listUser·p1.00:   39.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 140982
  mean =      6.809 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 2269 
    [ 5.000,  7.500) = 113729 
    [ 7.500, 10.000) = 21060 
    [10.000, 12.500) = 2600 
    [12.500, 15.000) = 714 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 70 
    [30.000, 32.500) = 82 
    [32.500, 35.000) = 38 
    [35.000, 37.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      6.496 ms/op
     p(90.0000) =      7.971 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.304 ms/op
     p(99.9000) =     30.933 ms/op
     p(99.9900) =     37.152 ms/op
     p(99.9990) =     39.923 ms/op
     p(99.9999) =     39.977 ms/op
    p(100.0000) =     39.977 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.125 ± 4.428  ops/ms
ClientPb.existUser                       thrpt       3   5.675 ± 3.815  ops/ms
ClientPb.getUser                         thrpt       3   5.486 ± 4.914  ops/ms
ClientPb.listUser                        thrpt       3   4.751 ± 1.557  ops/ms
ClientPb.createUser                       avgt       3   6.206 ± 6.799   ms/op
ClientPb.existUser                        avgt       3   5.604 ± 0.688   ms/op
ClientPb.getUser                          avgt       3   5.969 ± 2.322   ms/op
ClientPb.listUser                         avgt       3   6.928 ± 2.059   ms/op
ClientPb.createUser                     sample  160517   5.980 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.703           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.679           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.887           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.178           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.261           ms/op
ClientPb.existUser                      sample  164391   5.837 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.236           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.111           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.966           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.403           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.766           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.262           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.654           ms/op
ClientPb.getUser                        sample  159649   6.011 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.644           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.307           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.583           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.524           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.392           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.834           ms/op
ClientPb.listUser                       sample  140982   6.809 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.304           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.933           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.152           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.977           ms/op
