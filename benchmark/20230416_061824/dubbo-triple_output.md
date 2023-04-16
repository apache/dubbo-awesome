# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.506 ops/ms
# Warmup Iteration   2: 6.014 ops/ms
# Warmup Iteration   3: 9.113 ops/ms
Iteration   1: 9.512 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 10.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.873 ±(99.9%) 5.703 ops/ms [Average]
  (min, avg, max) = (9.512, 9.873, 10.057), stdev = 0.313
  CI (99.9%): [4.170, 15.576] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.469 ops/ms
# Warmup Iteration   2: 9.047 ops/ms
# Warmup Iteration   3: 10.004 ops/ms
Iteration   1: 10.146 ops/ms
Iteration   2: 10.546 ops/ms
Iteration   3: 10.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.423 ±(99.9%) 4.388 ops/ms [Average]
  (min, avg, max) = (10.146, 10.423, 10.577), stdev = 0.240
  CI (99.9%): [6.035, 14.810] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.499 ops/ms
# Warmup Iteration   2: 9.357 ops/ms
# Warmup Iteration   3: 9.943 ops/ms
Iteration   1: 10.048 ops/ms
Iteration   2: 10.243 ops/ms
Iteration   3: 9.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.986 ±(99.9%) 5.331 ops/ms [Average]
  (min, avg, max) = (9.668, 9.986, 10.243), stdev = 0.292
  CI (99.9%): [4.655, 15.317] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.231 ops/ms
# Warmup Iteration   2: 7.646 ops/ms
# Warmup Iteration   3: 8.180 ops/ms
Iteration   1: 8.539 ops/ms
Iteration   2: 8.757 ops/ms
Iteration   3: 8.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.590 ±(99.9%) 2.720 ops/ms [Average]
  (min, avg, max) = (8.472, 8.590, 8.757), stdev = 0.149
  CI (99.9%): [5.869, 11.310] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.871 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
Iteration   2: 3.183 ±(99.9%) 0.005 ms/op
Iteration   3: 3.383 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.229 ±(99.9%) 2.487 ms/op [Average]
  (min, avg, max) = (3.122, 3.229, 3.383), stdev = 0.136
  CI (99.9%): [0.742, 5.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.873 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.007 ms/op
Iteration   1: 3.175 ±(99.9%) 0.008 ms/op
Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
Iteration   3: 3.156 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.121 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (3.032, 3.121, 3.175), stdev = 0.078
  CI (99.9%): [1.705, 4.537] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.629 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.002 ms/op
Iteration   1: 3.112 ±(99.9%) 0.006 ms/op
Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
Iteration   3: 3.186 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.163 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.112, 3.163, 3.192), stdev = 0.044
  CI (99.9%): [2.355, 3.972] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.144 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.010 ms/op
Iteration   1: 3.705 ±(99.9%) 0.008 ms/op
Iteration   2: 3.709 ±(99.9%) 0.004 ms/op
Iteration   3: 3.752 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 0.471 ms/op [Average]
  (min, avg, max) = (3.705, 3.722, 3.752), stdev = 0.026
  CI (99.9%): [3.251, 4.193] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.174 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
Iteration   1: 3.295 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  18.406 ms/op
                 createUser·p0.9999: 21.112 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 22.023 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   3: 3.226 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  15.696 ms/op
                 createUser·p0.9999: 31.165 ms/op
                 createUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295382
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22916 
    [ 2.500,  5.000) = 264728 
    [ 5.000,  7.500) = 7004 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     16.752 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     31.265 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.540 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.008 ms/op
Iteration   1: 3.150 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  13.573 ms/op
                 existUser·p0.9999: 22.010 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.112 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.167 ms/op

Iteration   3: 3.121 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  14.736 ms/op
                 existUser·p0.9999: 22.634 ms/op
                 existUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306901
  mean =      3.127 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21924 
    [ 2.500,  5.000) = 279898 
    [ 5.000,  7.500) = 4342 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 181 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     14.452 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     25.814 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.687 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.476 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.371 ±(99.9%) 0.011 ms/op
Iteration   1: 3.153 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  9.561 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   2: 3.213 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  11.953 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  12.699 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 304050
  mean =      3.154 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10169 
    [ 2.500,  5.000) = 288244 
    [ 5.000,  7.500) = 4802 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 183 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      5.845 ms/op
     p(99.9000) =     11.894 ms/op
     p(99.9900) =     21.344 ms/op
     p(99.9990) =     22.248 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.384 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.011 ms/op
Iteration   1: 3.792 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.266 ms/op
                 listUser·p0.999:  15.521 ms/op
                 listUser·p0.9999: 21.589 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  13.894 ms/op
                 listUser·p0.9999: 14.483 ms/op
                 listUser·p1.00:   14.598 ms/op

Iteration   3: 3.717 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  13.451 ms/op
                 listUser·p0.9999: 14.729 ms/op
                 listUser·p1.00:   14.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254394
  mean =      3.771 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 245609 
    [ 5.000,  7.500) = 6908 
    [ 7.500, 10.000) = 1210 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 358 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     19.665 ms/op
     p(99.9990) =     21.984 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.873 ± 5.703  ops/ms
ClientPb.existUser                       thrpt       3  10.423 ± 4.388  ops/ms
ClientPb.getUser                         thrpt       3   9.986 ± 5.331  ops/ms
ClientPb.listUser                        thrpt       3   8.590 ± 2.720  ops/ms
ClientPb.createUser                       avgt       3   3.229 ± 2.487   ms/op
ClientPb.existUser                        avgt       3   3.121 ± 1.416   ms/op
ClientPb.getUser                          avgt       3   3.163 ± 0.808   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 0.471   ms/op
ClientPb.createUser                     sample  295382   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.797           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.752           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.393           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.654           ms/op
ClientPb.existUser                      sample  306901   3.127 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.204           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.449           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.452           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.413           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.837           ms/op
ClientPb.getUser                        sample  304050   3.154 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.932           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.473           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.699           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.845           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.894           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.344           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.478           ms/op
ClientPb.listUser                       sample  254394   3.771 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.894           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.413           ms/op
