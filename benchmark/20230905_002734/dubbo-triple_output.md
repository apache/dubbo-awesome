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
# Warmup Iteration   1: 1.172 ops/ms
# Warmup Iteration   2: 2.929 ops/ms
# Warmup Iteration   3: 5.540 ops/ms
Iteration   1: 5.633 ops/ms
Iteration   2: 5.803 ops/ms
Iteration   3: 6.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.822 ±(99.9%) 3.635 ops/ms [Average]
  (min, avg, max) = (5.633, 5.822, 6.030), stdev = 0.199
  CI (99.9%): [2.187, 9.457] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.734 ops/ms
# Warmup Iteration   2: 4.606 ops/ms
# Warmup Iteration   3: 5.828 ops/ms
Iteration   1: 6.071 ops/ms
Iteration   2: 6.063 ops/ms
Iteration   3: 6.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.100 ±(99.9%) 1.035 ops/ms [Average]
  (min, avg, max) = (6.063, 6.100, 6.165), stdev = 0.057
  CI (99.9%): [5.065, 7.134] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.771 ops/ms
# Warmup Iteration   2: 4.641 ops/ms
# Warmup Iteration   3: 5.838 ops/ms
Iteration   1: 5.925 ops/ms
Iteration   2: 5.988 ops/ms
Iteration   3: 5.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.930 ±(99.9%) 1.022 ops/ms [Average]
  (min, avg, max) = (5.876, 5.930, 5.988), stdev = 0.056
  CI (99.9%): [4.908, 6.951] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.564 ops/ms
# Warmup Iteration   2: 4.187 ops/ms
# Warmup Iteration   3: 5.214 ops/ms
Iteration   1: 5.004 ops/ms
Iteration   2: 4.935 ops/ms
Iteration   3: 5.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.986 ±(99.9%) 0.832 ops/ms [Average]
  (min, avg, max) = (4.935, 4.986, 5.021), stdev = 0.046
  CI (99.9%): [4.155, 5.818] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 17.808 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.202 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.847 ±(99.9%) 0.010 ms/op
Iteration   1: 5.327 ±(99.9%) 0.020 ms/op
Iteration   2: 5.613 ±(99.9%) 0.009 ms/op
Iteration   3: 5.328 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.423 ±(99.9%) 3.010 ms/op [Average]
  (min, avg, max) = (5.327, 5.423, 5.613), stdev = 0.165
  CI (99.9%): [2.413, 8.432] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 16.827 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.962 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 5.263 ±(99.9%) 0.010 ms/op
Iteration   1: 5.327 ±(99.9%) 0.008 ms/op
Iteration   2: 5.242 ±(99.9%) 0.010 ms/op
Iteration   3: 5.263 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.277 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (5.242, 5.277, 5.327), stdev = 0.044
  CI (99.9%): [4.470, 6.083] (assumes normal distribution)


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
# Warmup Iteration   1: 15.638 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.399 ±(99.9%) 0.010 ms/op
Iteration   1: 5.468 ±(99.9%) 0.006 ms/op
Iteration   2: 5.265 ±(99.9%) 0.011 ms/op
Iteration   3: 5.155 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.296 ±(99.9%) 2.901 ms/op [Average]
  (min, avg, max) = (5.155, 5.296, 5.468), stdev = 0.159
  CI (99.9%): [2.395, 8.197] (assumes normal distribution)


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
# Warmup Iteration   1: 18.336 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 7.800 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.265 ±(99.9%) 0.013 ms/op
Iteration   1: 6.321 ±(99.9%) 0.016 ms/op
Iteration   2: 6.383 ±(99.9%) 0.010 ms/op
Iteration   3: 6.275 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.326 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (6.275, 6.326, 6.383), stdev = 0.054
  CI (99.9%): [5.333, 7.320] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.988 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 7.395 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.899 ±(99.9%) 0.025 ms/op
Iteration   1: 5.466 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.339 ms/op
                 createUser·p0.50:   5.136 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.487 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  23.686 ms/op
                 createUser·p0.9999: 28.064 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   2: 5.486 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.046 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   6.603 ms/op
                 createUser·p0.95:   7.274 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  16.635 ms/op
                 createUser·p0.9999: 28.841 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   3: 5.344 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.087 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.332 ms/op
                 createUser·p0.95:   7.102 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  26.977 ms/op
                 createUser·p0.9999: 30.596 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176684
  mean =      5.431 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 71207 
    [ 5.000,  7.500) = 97639 
    [ 7.500, 10.000) = 5877 
    [10.000, 12.500) = 1259 
    [12.500, 15.000) = 429 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.046 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.307 ms/op
     p(99.0000) =     10.210 ms/op
     p(99.9000) =     18.686 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     34.749 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 16.120 ±(99.9%) 0.241 ms/op
# Warmup Iteration   2: 5.849 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.275 ±(99.9%) 0.017 ms/op
Iteration   1: 5.280 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.874 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.184 ms/op
                 existUser·p0.99:   9.273 ms/op
                 existUser·p0.999:  22.807 ms/op
                 existUser·p0.9999: 25.913 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   2: 5.133 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.232 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.046 ms/op
                 existUser·p0.95:   7.315 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  25.004 ms/op
                 existUser·p0.9999: 29.877 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   3: 5.303 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.544 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   6.529 ms/op
                 existUser·p0.95:   7.487 ms/op
                 existUser·p0.99:   10.502 ms/op
                 existUser·p0.999:  16.281 ms/op
                 existUser·p0.9999: 30.769 ms/op
                 existUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183147
  mean =      5.238 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 97345 
    [ 5.000,  7.500) = 77342 
    [ 7.500, 10.000) = 6775 
    [10.000, 12.500) = 1084 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.324 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     19.132 ms/op
     p(99.9900) =     29.907 ms/op
     p(99.9990) =     31.169 ms/op
     p(99.9999) =     31.523 ms/op
    p(100.0000) =     31.523 ms/op


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
# Warmup Iteration   1: 16.310 ±(99.9%) 0.298 ms/op
# Warmup Iteration   2: 6.198 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.683 ±(99.9%) 0.019 ms/op
Iteration   1: 5.554 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.904 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.774 ms/op
                 getUser·p0.99:   11.141 ms/op
                 getUser·p0.999:  22.452 ms/op
                 getUser·p0.9999: 31.521 ms/op
                 getUser·p1.00:   32.080 ms/op

Iteration   2: 5.427 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.477 ms/op
                 getUser·p0.50:   5.054 ms/op
                 getUser·p0.90:   6.660 ms/op
                 getUser·p0.95:   8.151 ms/op
                 getUser·p0.99:   11.616 ms/op
                 getUser·p0.999:  22.842 ms/op
                 getUser·p0.9999: 26.251 ms/op
                 getUser·p1.00:   30.081 ms/op

Iteration   3: 5.321 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.843 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.308 ms/op
                 getUser·p0.95:   7.062 ms/op
                 getUser·p0.99:   10.792 ms/op
                 getUser·p0.999:  24.047 ms/op
                 getUser·p0.9999: 26.503 ms/op
                 getUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176624
  mean =      5.432 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 74436 
    [ 5.000,  7.500) = 92554 
    [ 7.500, 10.000) = 6882 
    [10.000, 12.500) = 1652 
    [12.500, 15.000) = 596 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.477 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.668 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     23.245 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     32.080 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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
# Warmup Iteration   1: 19.038 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 7.635 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.475 ±(99.9%) 0.025 ms/op
Iteration   1: 6.275 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  24.544 ms/op
                 listUser·p0.9999: 29.183 ms/op
                 listUser·p1.00:   31.883 ms/op

Iteration   2: 6.232 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.408 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  30.409 ms/op
                 listUser·p0.9999: 33.517 ms/op
                 listUser·p1.00:   34.275 ms/op

Iteration   3: 6.156 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   3.289 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.160 ms/op
                 listUser·p0.95:   8.182 ms/op
                 listUser·p0.99:   12.354 ms/op
                 listUser·p0.999:  23.927 ms/op
                 listUser·p0.9999: 26.956 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154263
  mean =      6.221 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 6862 
    [ 5.000,  7.500) = 134430 
    [ 7.500, 10.000) = 9442 
    [10.000, 12.500) = 2208 
    [12.500, 15.000) = 641 
    [15.000, 17.500) = 305 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.417 ms/op
     p(50.0000) =      5.890 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.356 ms/op
     p(99.0000) =     12.075 ms/op
     p(99.9000) =     25.952 ms/op
     p(99.9900) =     31.841 ms/op
     p(99.9990) =     33.955 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.822 ± 3.635  ops/ms
ClientPb.existUser                       thrpt       3   6.100 ± 1.035  ops/ms
ClientPb.getUser                         thrpt       3   5.930 ± 1.022  ops/ms
ClientPb.listUser                        thrpt       3   4.986 ± 0.832  ops/ms
ClientPb.createUser                       avgt       3   5.423 ± 3.010   ms/op
ClientPb.existUser                        avgt       3   5.277 ± 0.807   ms/op
ClientPb.getUser                          avgt       3   5.296 ± 2.901   ms/op
ClientPb.listUser                         avgt       3   6.326 ± 0.994   ms/op
ClientPb.createUser                     sample  176684   5.431 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.046           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.161           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.570           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.307           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.210           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.686           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.655           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  183147   5.238 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.956           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.341           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.324           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.781           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.132           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.907           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.523           ms/op
ClientPb.getUser                        sample  176624   5.432 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.128           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.668           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.207           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.245           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.917           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.080           ms/op
ClientPb.listUser                       sample  154263   6.221 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.890           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.356           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.075           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.952           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.841           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.275           ms/op
