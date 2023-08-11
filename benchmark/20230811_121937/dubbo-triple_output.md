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
# Warmup Iteration   1: 1.324 ops/ms
# Warmup Iteration   2: 2.947 ops/ms
# Warmup Iteration   3: 5.908 ops/ms
Iteration   1: 6.080 ops/ms
Iteration   2: 6.324 ops/ms
Iteration   3: 6.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.294 ±(99.9%) 3.645 ops/ms [Average]
  (min, avg, max) = (6.080, 6.294, 6.476), stdev = 0.200
  CI (99.9%): [2.649, 9.938] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 5.294 ops/ms
# Warmup Iteration   3: 6.343 ops/ms
Iteration   1: 6.580 ops/ms
Iteration   2: 6.691 ops/ms
Iteration   3: 6.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.589 ±(99.9%) 1.781 ops/ms [Average]
  (min, avg, max) = (6.496, 6.589, 6.691), stdev = 0.098
  CI (99.9%): [4.808, 8.370] (assumes normal distribution)


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
# Warmup Iteration   1: 1.893 ops/ms
# Warmup Iteration   2: 5.249 ops/ms
# Warmup Iteration   3: 6.092 ops/ms
Iteration   1: 6.248 ops/ms
Iteration   2: 6.174 ops/ms
Iteration   3: 6.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.171 ±(99.9%) 1.439 ops/ms [Average]
  (min, avg, max) = (6.091, 6.171, 6.248), stdev = 0.079
  CI (99.9%): [4.732, 7.610] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 1.756 ops/ms
# Warmup Iteration   2: 4.770 ops/ms
# Warmup Iteration   3: 5.452 ops/ms
Iteration   1: 5.267 ops/ms
Iteration   2: 5.313 ops/ms
Iteration   3: 5.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.329 ±(99.9%) 1.308 ops/ms [Average]
  (min, avg, max) = (5.267, 5.329, 5.408), stdev = 0.072
  CI (99.9%): [4.021, 6.638] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 16.809 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.285 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.323 ±(99.9%) 0.016 ms/op
Iteration   1: 5.237 ±(99.9%) 0.010 ms/op
Iteration   2: 5.196 ±(99.9%) 0.006 ms/op
Iteration   3: 5.054 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.162 ±(99.9%) 1.751 ms/op [Average]
  (min, avg, max) = (5.054, 5.162, 5.237), stdev = 0.096
  CI (99.9%): [3.412, 6.913] (assumes normal distribution)


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
# Warmup Iteration   1: 14.978 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.478 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.009 ±(99.9%) 0.007 ms/op
Iteration   1: 4.899 ±(99.9%) 0.009 ms/op
Iteration   2: 4.809 ±(99.9%) 0.011 ms/op
Iteration   3: 4.878 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.862 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (4.809, 4.862, 4.899), stdev = 0.047
  CI (99.9%): [3.998, 5.727] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.948 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.594 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.427 ±(99.9%) 0.008 ms/op
Iteration   1: 5.316 ±(99.9%) 0.006 ms/op
Iteration   2: 5.111 ±(99.9%) 0.012 ms/op
Iteration   3: 5.216 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.214 ±(99.9%) 1.869 ms/op [Average]
  (min, avg, max) = (5.111, 5.214, 5.316), stdev = 0.102
  CI (99.9%): [3.345, 7.083] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.583 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.137 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.133 ±(99.9%) 0.010 ms/op
Iteration   1: 5.857 ±(99.9%) 0.015 ms/op
Iteration   2: 6.127 ±(99.9%) 0.008 ms/op
Iteration   3: 5.945 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.976 ±(99.9%) 2.509 ms/op [Average]
  (min, avg, max) = (5.857, 5.976, 6.127), stdev = 0.138
  CI (99.9%): [3.467, 8.486] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 16.505 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 6.837 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.464 ±(99.9%) 0.022 ms/op
Iteration   1: 5.092 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.417 ms/op
                 createUser·p0.50:   4.841 ms/op
                 createUser·p0.90:   5.906 ms/op
                 createUser·p0.95:   6.939 ms/op
                 createUser·p0.99:   9.978 ms/op
                 createUser·p0.999:  22.159 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 5.203 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.283 ms/op
                 createUser·p0.95:   7.143 ms/op
                 createUser·p0.99:   9.929 ms/op
                 createUser·p0.999:  26.477 ms/op
                 createUser·p0.9999: 34.621 ms/op
                 createUser·p1.00:   36.569 ms/op

Iteration   3: 5.255 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.302 ms/op
                 createUser·p0.50:   4.956 ms/op
                 createUser·p0.90:   6.300 ms/op
                 createUser·p0.95:   7.520 ms/op
                 createUser·p0.99:   10.486 ms/op
                 createUser·p0.999:  25.065 ms/op
                 createUser·p0.9999: 29.224 ms/op
                 createUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 185035
  mean =      5.182 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 105377 
    [ 5.000,  7.500) = 71418 
    [ 7.500, 10.000) = 6278 
    [10.000, 12.500) = 1304 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.160 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     23.821 ms/op
     p(99.9900) =     29.409 ms/op
     p(99.9990) =     36.402 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.298 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 5.853 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.969 ±(99.9%) 0.015 ms/op
Iteration   1: 4.951 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   5.849 ms/op
                 existUser·p0.95:   6.570 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  21.551 ms/op
                 existUser·p0.9999: 26.461 ms/op
                 existUser·p1.00:   27.034 ms/op

Iteration   2: 4.811 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   4.530 ms/op
                 existUser·p0.90:   5.833 ms/op
                 existUser·p0.95:   6.504 ms/op
                 existUser·p0.99:   8.700 ms/op
                 existUser·p0.999:  14.394 ms/op
                 existUser·p0.9999: 26.359 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   3: 5.002 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.872 ms/op
                 existUser·p0.50:   4.686 ms/op
                 existUser·p0.90:   6.054 ms/op
                 existUser·p0.95:   6.947 ms/op
                 existUser·p0.99:   10.027 ms/op
                 existUser·p0.999:  22.971 ms/op
                 existUser·p0.9999: 30.887 ms/op
                 existUser·p1.00:   31.556 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 195115
  mean =      4.920 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 141011 
    [ 5.000,  7.500) = 48087 
    [ 7.500, 10.000) = 4461 
    [10.000, 12.500) = 942 
    [12.500, 15.000) = 324 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.906 ms/op
     p(95.0000) =      6.693 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     21.313 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     31.275 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.907 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 5.720 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.492 ±(99.9%) 0.019 ms/op
Iteration   1: 5.240 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.594 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.660 ms/op
                 getUser·p0.95:   8.184 ms/op
                 getUser·p0.99:   11.338 ms/op
                 getUser·p0.999:  23.392 ms/op
                 getUser·p0.9999: 31.031 ms/op
                 getUser·p1.00:   32.244 ms/op

Iteration   2: 5.225 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.021 ms/op
                 getUser·p0.95:   7.086 ms/op
                 getUser·p0.99:   9.762 ms/op
                 getUser·p0.999:  23.214 ms/op
                 getUser·p0.9999: 26.427 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   3: 5.199 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.380 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.144 ms/op
                 getUser·p0.95:   7.643 ms/op
                 getUser·p0.99:   10.781 ms/op
                 getUser·p0.999:  24.042 ms/op
                 getUser·p0.9999: 28.455 ms/op
                 getUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183891
  mean =      5.221 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 104647 
    [ 5.000,  7.500) = 68831 
    [ 7.500, 10.000) = 8023 
    [10.000, 12.500) = 1593 
    [12.500, 15.000) = 428 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 88 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     23.436 ms/op
     p(99.9900) =     30.516 ms/op
     p(99.9990) =     31.941 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.906 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 7.486 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.245 ±(99.9%) 0.023 ms/op
Iteration   1: 5.918 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.199 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  25.231 ms/op
                 listUser·p0.9999: 28.500 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   2: 5.921 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  26.666 ms/op
                 listUser·p0.9999: 31.778 ms/op
                 listUser·p1.00:   32.571 ms/op

Iteration   3: 5.922 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.526 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   8.192 ms/op
                 listUser·p0.99:   11.928 ms/op
                 listUser·p0.999:  21.956 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 162082
  mean =      5.921 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 12483 
    [ 5.000,  7.500) = 137861 
    [ 7.500, 10.000) = 8275 
    [10.000, 12.500) = 2229 
    [12.500, 15.000) = 652 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     11.895 ms/op
     p(99.9000) =     25.035 ms/op
     p(99.9900) =     30.559 ms/op
     p(99.9990) =     32.327 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.294 ± 3.645  ops/ms
ClientPb.existUser                       thrpt       3   6.589 ± 1.781  ops/ms
ClientPb.getUser                         thrpt       3   6.171 ± 1.439  ops/ms
ClientPb.listUser                        thrpt       3   5.329 ± 1.308  ops/ms
ClientPb.createUser                       avgt       3   5.162 ± 1.751   ms/op
ClientPb.existUser                        avgt       3   4.862 ± 0.865   ms/op
ClientPb.getUser                          avgt       3   5.214 ± 1.869   ms/op
ClientPb.listUser                         avgt       3   5.976 ± 2.509   ms/op
ClientPb.createUser                     sample  185035   5.182 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.790           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.907           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.160           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.315           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.142           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.821           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.409           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.569           ms/op
ClientPb.existUser                      sample  195115   4.920 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.634           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.693           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.454           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.313           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.393           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.556           ms/op
ClientPb.getUser                        sample  183891   5.221 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.594           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.210           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.774           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.748           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.436           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.516           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.244           ms/op
ClientPb.listUser                       sample  162082   5.921 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.526           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.922           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.454           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.895           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.035           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.559           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.571           ms/op
