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
# Warmup Iteration   1: 1.261 ops/ms
# Warmup Iteration   2: 2.675 ops/ms
# Warmup Iteration   3: 5.323 ops/ms
Iteration   1: 5.538 ops/ms
Iteration   2: 5.608 ops/ms
Iteration   3: 5.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.691 ±(99.9%) 3.793 ops/ms [Average]
  (min, avg, max) = (5.538, 5.691, 5.928), stdev = 0.208
  CI (99.9%): [1.898, 9.484] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.466 ops/ms
# Warmup Iteration   2: 5.262 ops/ms
# Warmup Iteration   3: 5.968 ops/ms
Iteration   1: 5.956 ops/ms
Iteration   2: 6.179 ops/ms
Iteration   3: 6.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.174 ±(99.9%) 3.925 ops/ms [Average]
  (min, avg, max) = (5.956, 6.174, 6.386), stdev = 0.215
  CI (99.9%): [2.249, 10.099] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.665 ops/ms
# Warmup Iteration   2: 4.588 ops/ms
# Warmup Iteration   3: 5.732 ops/ms
Iteration   1: 5.705 ops/ms
Iteration   2: 5.852 ops/ms
Iteration   3: 6.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.900 ±(99.9%) 4.078 ops/ms [Average]
  (min, avg, max) = (5.705, 5.900, 6.144), stdev = 0.224
  CI (99.9%): [1.822, 9.979] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.531 ops/ms
# Warmup Iteration   2: 4.023 ops/ms
# Warmup Iteration   3: 5.301 ops/ms
Iteration   1: 5.146 ops/ms
Iteration   2: 5.036 ops/ms
Iteration   3: 5.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.143 ±(99.9%) 1.910 ops/ms [Average]
  (min, avg, max) = (5.036, 5.143, 5.246), stdev = 0.105
  CI (99.9%): [3.233, 7.052] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.534 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 6.672 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.557 ±(99.9%) 0.011 ms/op
Iteration   1: 5.518 ±(99.9%) 0.012 ms/op
Iteration   2: 5.416 ±(99.9%) 0.015 ms/op
Iteration   3: 5.366 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.433 ±(99.9%) 1.411 ms/op [Average]
  (min, avg, max) = (5.366, 5.433, 5.518), stdev = 0.077
  CI (99.9%): [4.022, 6.845] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.462 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 6.380 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.136 ±(99.9%) 0.011 ms/op
Iteration   1: 5.182 ±(99.9%) 0.009 ms/op
Iteration   2: 5.168 ±(99.9%) 0.013 ms/op
Iteration   3: 5.134 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.161 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (5.134, 5.161, 5.182), stdev = 0.025
  CI (99.9%): [4.711, 5.612] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 17.568 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.360 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.796 ±(99.9%) 0.009 ms/op
Iteration   1: 5.427 ±(99.9%) 0.012 ms/op
Iteration   2: 5.474 ±(99.9%) 0.010 ms/op
Iteration   3: 5.600 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.500 ±(99.9%) 1.629 ms/op [Average]
  (min, avg, max) = (5.427, 5.500, 5.600), stdev = 0.089
  CI (99.9%): [3.872, 7.129] (assumes normal distribution)


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
# Warmup Iteration   1: 18.746 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 8.710 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 6.705 ±(99.9%) 0.012 ms/op
Iteration   1: 6.458 ±(99.9%) 0.017 ms/op
Iteration   2: 6.277 ±(99.9%) 0.021 ms/op
Iteration   3: 6.417 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.384 ±(99.9%) 1.727 ms/op [Average]
  (min, avg, max) = (6.277, 6.384, 6.458), stdev = 0.095
  CI (99.9%): [4.657, 8.111] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.039 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 6.817 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.127 ±(99.9%) 0.029 ms/op
Iteration   1: 5.683 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.081 ms/op
                 createUser·p0.50:   5.448 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   7.848 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  24.742 ms/op
                 createUser·p0.9999: 33.889 ms/op
                 createUser·p1.00:   34.931 ms/op

Iteration   2: 5.428 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  25.106 ms/op
                 createUser·p0.9999: 29.509 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   3: 5.325 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.058 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.382 ms/op
                 createUser·p0.95:   7.193 ms/op
                 createUser·p0.99:   9.670 ms/op
                 createUser·p0.999:  15.984 ms/op
                 createUser·p0.9999: 26.966 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175309
  mean =      5.475 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 63321 
    [ 5.000,  7.500) = 102760 
    [ 7.500, 10.000) = 7325 
    [10.000, 12.500) = 1263 
    [12.500, 15.000) = 307 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.058 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     20.104 ms/op
     p(99.9900) =     31.652 ms/op
     p(99.9990) =     34.536 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 15.689 ±(99.9%) 0.245 ms/op
# Warmup Iteration   2: 6.496 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.478 ±(99.9%) 0.020 ms/op
Iteration   1: 5.468 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.794 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.709 ms/op
                 existUser·p0.95:   7.668 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  14.025 ms/op
                 existUser·p0.9999: 28.054 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   2: 5.355 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.458 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.193 ms/op
                 existUser·p0.99:   10.519 ms/op
                 existUser·p0.999:  26.238 ms/op
                 existUser·p0.9999: 29.955 ms/op
                 existUser·p1.00:   30.376 ms/op

Iteration   3: 5.307 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.359 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.341 ms/op
                 existUser·p0.95:   7.455 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  28.017 ms/op
                 existUser·p0.9999: 30.637 ms/op
                 existUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178457
  mean =      5.376 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 73574 
    [ 5.000,  7.500) = 96271 
    [ 7.500, 10.000) = 6644 
    [10.000, 12.500) = 1308 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     30.147 ms/op
     p(99.9990) =     31.165 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 16.836 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.903 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.812 ±(99.9%) 0.022 ms/op
Iteration   1: 5.452 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.916 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.791 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   10.617 ms/op
                 getUser·p0.999:  15.188 ms/op
                 getUser·p0.9999: 30.151 ms/op
                 getUser·p1.00:   31.785 ms/op

Iteration   2: 5.223 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   6.775 ms/op
                 getUser·p0.99:   9.077 ms/op
                 getUser·p0.999:  26.508 ms/op
                 getUser·p0.9999: 30.429 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 5.456 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.866 ms/op
                 getUser·p0.50:   5.243 ms/op
                 getUser·p0.90:   6.636 ms/op
                 getUser·p0.95:   7.397 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  29.370 ms/op
                 getUser·p0.9999: 34.227 ms/op
                 getUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178603
  mean =      5.375 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 68390 
    [ 5.000,  7.500) = 102467 
    [ 7.500, 10.000) = 5990 
    [10.000, 12.500) = 1097 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.866 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =      9.945 ms/op
     p(99.9000) =     26.358 ms/op
     p(99.9900) =     33.156 ms/op
     p(99.9990) =     35.665 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 20.725 ±(99.9%) 0.333 ms/op
# Warmup Iteration   2: 7.597 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 6.689 ±(99.9%) 0.024 ms/op
Iteration   1: 6.453 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   6.177 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.618 ms/op
                 listUser·p0.99:   12.198 ms/op
                 listUser·p0.999:  27.394 ms/op
                 listUser·p0.9999: 30.214 ms/op
                 listUser·p1.00:   31.654 ms/op

Iteration   2: 6.399 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.646 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   7.782 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  28.053 ms/op
                 listUser·p0.9999: 31.720 ms/op
                 listUser·p1.00:   32.702 ms/op

Iteration   3: 6.138 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   6.955 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  22.137 ms/op
                 listUser·p0.9999: 27.734 ms/op
                 listUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151617
  mean =      6.327 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 7025 
    [ 5.000,  7.500) = 130683 
    [ 7.500, 10.000) = 10316 
    [10.000, 12.500) = 2484 
    [12.500, 15.000) = 703 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      6.062 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.665 ms/op
     p(99.9000) =     27.165 ms/op
     p(99.9900) =     31.021 ms/op
     p(99.9990) =     32.669 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.691 ± 3.793  ops/ms
ClientPb.existUser                       thrpt       3   6.174 ± 3.925  ops/ms
ClientPb.getUser                         thrpt       3   5.900 ± 4.078  ops/ms
ClientPb.listUser                        thrpt       3   5.143 ± 1.910  ops/ms
ClientPb.createUser                       avgt       3   5.433 ± 1.411   ms/op
ClientPb.existUser                        avgt       3   5.161 ± 0.450   ms/op
ClientPb.getUser                          avgt       3   5.500 ± 1.629   ms/op
ClientPb.listUser                         avgt       3   6.384 ± 1.727   ms/op
ClientPb.createUser                     sample  175309   5.475 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.058           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.226           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.676           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.569           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.174           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.104           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.652           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.931           ms/op
ClientPb.existUser                      sample  178457   5.376 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.794           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.153           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.455           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.191           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.809           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.147           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.654           ms/op
ClientPb.getUser                        sample  178603   5.375 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.866           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.307           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.945           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.358           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.438           ms/op
ClientPb.listUser                       sample  151617   6.327 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.062           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.397           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.665           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.165           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.021           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.702           ms/op
