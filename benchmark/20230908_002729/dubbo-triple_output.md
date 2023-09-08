# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.067 ops/ms
# Warmup Iteration   2: 4.923 ops/ms
# Warmup Iteration   3: 8.492 ops/ms
Iteration   1: 8.955 ops/ms
Iteration   2: 9.004 ops/ms
Iteration   3: 9.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.122 ±(99.9%) 4.519 ops/ms [Average]
  (min, avg, max) = (8.955, 9.122, 9.407), stdev = 0.248
  CI (99.9%): [4.603, 13.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 8.840 ops/ms
# Warmup Iteration   3: 9.365 ops/ms
Iteration   1: 9.815 ops/ms
Iteration   2: 9.670 ops/ms
Iteration   3: 9.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.817 ±(99.9%) 2.700 ops/ms [Average]
  (min, avg, max) = (9.670, 9.817, 9.966), stdev = 0.148
  CI (99.9%): [7.117, 12.517] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.832 ops/ms
# Warmup Iteration   2: 8.616 ops/ms
# Warmup Iteration   3: 8.735 ops/ms
Iteration   1: 9.424 ops/ms
Iteration   2: 9.279 ops/ms
Iteration   3: 9.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.314 ±(99.9%) 1.767 ops/ms [Average]
  (min, avg, max) = (9.240, 9.314, 9.424), stdev = 0.097
  CI (99.9%): [7.547, 11.081] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 7.258 ops/ms
# Warmup Iteration   3: 7.847 ops/ms
Iteration   1: 7.855 ops/ms
Iteration   2: 7.983 ops/ms
Iteration   3: 7.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.930 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (7.855, 7.930, 7.983), stdev = 0.067
  CI (99.9%): [6.704, 9.157] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.404 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.726 ±(99.9%) 0.007 ms/op
Iteration   1: 3.491 ±(99.9%) 0.004 ms/op
Iteration   2: 3.406 ±(99.9%) 0.008 ms/op
Iteration   3: 3.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 0.849 ms/op [Average]
  (min, avg, max) = (3.406, 3.459, 3.491), stdev = 0.047
  CI (99.9%): [2.611, 4.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.183 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.005 ms/op
Iteration   1: 3.268 ±(99.9%) 0.008 ms/op
Iteration   2: 3.402 ±(99.9%) 0.006 ms/op
Iteration   3: 3.282 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.317 ±(99.9%) 1.338 ms/op [Average]
  (min, avg, max) = (3.268, 3.317, 3.402), stdev = 0.073
  CI (99.9%): [1.979, 4.656] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.698 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.596 ±(99.9%) 0.005 ms/op
Iteration   1: 3.473 ±(99.9%) 0.009 ms/op
Iteration   2: 3.501 ±(99.9%) 0.006 ms/op
Iteration   3: 3.370 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.448 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.370, 3.448, 3.501), stdev = 0.069
  CI (99.9%): [2.191, 4.705] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.901 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.423 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.007 ms/op
Iteration   1: 4.059 ±(99.9%) 0.009 ms/op
Iteration   2: 3.985 ±(99.9%) 0.014 ms/op
Iteration   3: 4.051 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.032 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.985, 4.032, 4.059), stdev = 0.041
  CI (99.9%): [3.287, 4.777] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.594 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.535 ±(99.9%) 0.011 ms/op
Iteration   1: 3.506 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   4.145 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.901 ms/op
                 createUser·p0.999:  17.999 ms/op
                 createUser·p0.9999: 21.314 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.493 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  20.939 ms/op
                 createUser·p0.9999: 26.841 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 3.529 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  18.052 ms/op
                 createUser·p0.9999: 24.934 ms/op
                 createUser·p1.00:   25.559 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273534
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5959 
    [ 2.500,  5.000) = 256377 
    [ 5.000,  7.500) = 9538 
    [ 7.500, 10.000) = 1075 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     18.839 ms/op
     p(99.9900) =     25.601 ms/op
     p(99.9990) =     27.462 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.462 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
Iteration   1: 3.284 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  12.001 ms/op
                 existUser·p0.9999: 25.404 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   2: 3.409 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  19.885 ms/op
                 existUser·p0.9999: 30.188 ms/op
                 existUser·p1.00:   31.916 ms/op

Iteration   3: 3.463 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.360 ms/op
                 existUser·p0.999:  19.728 ms/op
                 existUser·p0.9999: 26.468 ms/op
                 existUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283523
  mean =      3.384 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8232 
    [ 2.500,  5.000) = 265998 
    [ 5.000,  7.500) = 7822 
    [ 7.500, 10.000) = 998 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     19.725 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.457 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.012 ms/op
Iteration   1: 3.433 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.931 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  10.416 ms/op
                 getUser·p0.9999: 22.304 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   2: 3.375 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.276 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  21.109 ms/op
                 getUser·p0.9999: 30.787 ms/op
                 getUser·p1.00:   31.982 ms/op

Iteration   3: 3.468 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  21.193 ms/op
                 getUser·p0.9999: 29.083 ms/op
                 getUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280115
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4878 
    [ 2.500,  5.000) = 268870 
    [ 5.000,  7.500) = 4741 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     29.261 ms/op
     p(99.9990) =     31.379 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.735 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.510 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.227 ±(99.9%) 0.014 ms/op
Iteration   1: 4.081 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  21.741 ms/op
                 listUser·p0.9999: 24.586 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   2: 4.220 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  16.147 ms/op
                 listUser·p0.9999: 22.540 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 4.156 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 22.446 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231130
  mean =      4.151 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 217669 
    [ 5.000,  7.500) = 10199 
    [ 7.500, 10.000) = 2126 
    [10.000, 12.500) = 555 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.928 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.122 ± 4.519  ops/ms
ClientPb.existUser                       thrpt       3   9.817 ± 2.700  ops/ms
ClientPb.getUser                         thrpt       3   9.314 ± 1.767  ops/ms
ClientPb.listUser                        thrpt       3   7.930 ± 1.227  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 0.849   ms/op
ClientPb.existUser                        avgt       3   3.317 ± 1.338   ms/op
ClientPb.getUser                          avgt       3   3.448 ± 1.257   ms/op
ClientPb.listUser                         avgt       3   4.032 ± 0.745   ms/op
ClientPb.createUser                     sample  273534   3.509 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.079           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.628           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.636           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.839           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.601           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.591           ms/op
ClientPb.existUser                      sample  283523   3.384 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.605           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.358           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.725           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.262           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  280115   3.425 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.276           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.715           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.261           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.982           ms/op
ClientPb.listUser                       sample  231130   4.151 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.456           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.226           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.102           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.117           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.297           ms/op
