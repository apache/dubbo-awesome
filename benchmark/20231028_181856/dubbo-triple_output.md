# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.532 ops/ms
# Warmup Iteration   2: 3.322 ops/ms
# Warmup Iteration   3: 6.984 ops/ms
Iteration   1: 7.193 ops/ms
Iteration   2: 7.845 ops/ms
Iteration   3: 7.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.486 ±(99.9%) 6.042 ops/ms [Average]
  (min, avg, max) = (7.193, 7.486, 7.845), stdev = 0.331
  CI (99.9%): [1.444, 13.528] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.170 ops/ms
# Warmup Iteration   2: 6.758 ops/ms
# Warmup Iteration   3: 7.766 ops/ms
Iteration   1: 7.928 ops/ms
Iteration   2: 7.957 ops/ms
Iteration   3: 8.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.964 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (7.928, 7.964, 8.007), stdev = 0.040
  CI (99.9%): [7.232, 8.696] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.113 ops/ms
# Warmup Iteration   2: 6.369 ops/ms
# Warmup Iteration   3: 7.360 ops/ms
Iteration   1: 7.585 ops/ms
Iteration   2: 7.807 ops/ms
Iteration   3: 7.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.712 ±(99.9%) 2.085 ops/ms [Average]
  (min, avg, max) = (7.585, 7.712, 7.807), stdev = 0.114
  CI (99.9%): [5.627, 9.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.081 ops/ms
# Warmup Iteration   2: 5.488 ops/ms
# Warmup Iteration   3: 6.190 ops/ms
Iteration   1: 6.496 ops/ms
Iteration   2: 6.345 ops/ms
Iteration   3: 6.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.472 ±(99.9%) 2.135 ops/ms [Average]
  (min, avg, max) = (6.345, 6.472, 6.575), stdev = 0.117
  CI (99.9%): [4.337, 8.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.277 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.917 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.373 ±(99.9%) 0.005 ms/op
Iteration   1: 4.312 ±(99.9%) 0.005 ms/op
Iteration   2: 4.075 ±(99.9%) 0.005 ms/op
Iteration   3: 4.086 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.157 ±(99.9%) 2.438 ms/op [Average]
  (min, avg, max) = (4.075, 4.157, 4.312), stdev = 0.134
  CI (99.9%): [1.719, 6.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.287 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.003 ms/op
Iteration   1: 3.948 ±(99.9%) 0.005 ms/op
Iteration   2: 3.890 ±(99.9%) 0.008 ms/op
Iteration   3: 3.935 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.924 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.890, 3.924, 3.948), stdev = 0.030
  CI (99.9%): [3.368, 4.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.430 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.414 ±(99.9%) 0.003 ms/op
Iteration   1: 4.131 ±(99.9%) 0.002 ms/op
Iteration   2: 4.186 ±(99.9%) 0.005 ms/op
Iteration   3: 4.148 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.155 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (4.131, 4.155, 4.186), stdev = 0.028
  CI (99.9%): [3.643, 4.668] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.043 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.254 ±(99.9%) 0.008 ms/op
Iteration   1: 5.044 ±(99.9%) 0.009 ms/op
Iteration   2: 4.941 ±(99.9%) 0.008 ms/op
Iteration   3: 4.973 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.986 ±(99.9%) 0.955 ms/op [Average]
  (min, avg, max) = (4.941, 4.986, 5.044), stdev = 0.052
  CI (99.9%): [4.031, 5.941] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.102 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 5.516 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.557 ±(99.9%) 0.018 ms/op
Iteration   1: 4.150 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.961 ms/op
                 createUser·p0.90:   4.801 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  23.364 ms/op
                 createUser·p0.9999: 27.114 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 4.093 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.169 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  15.809 ms/op
                 createUser·p0.9999: 29.575 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   3: 4.030 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.774 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  29.749 ms/op
                 createUser·p0.9999: 33.360 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234677
  mean =      4.090 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 202 
    [ 2.500,  5.000) = 220175 
    [ 5.000,  7.500) = 11845 
    [ 7.500, 10.000) = 1614 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     23.494 ms/op
     p(99.9900) =     31.835 ms/op
     p(99.9990) =     33.748 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.353 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.708 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
Iteration   1: 3.894 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.842 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 24.969 ms/op
                 existUser·p1.00:   25.428 ms/op

Iteration   2: 3.933 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   8.249 ms/op
                 existUser·p0.999:  25.498 ms/op
                 existUser·p0.9999: 29.531 ms/op
                 existUser·p1.00:   30.310 ms/op

Iteration   3: 3.943 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.845 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  18.472 ms/op
                 existUser·p0.9999: 30.798 ms/op
                 existUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244645
  mean =      3.923 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 161 
    [ 2.500,  5.000) = 234941 
    [ 5.000,  7.500) = 7630 
    [ 7.500, 10.000) = 1118 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     22.949 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     31.737 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.426 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.634 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.210 ±(99.9%) 0.014 ms/op
Iteration   1: 4.206 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   8.955 ms/op
                 getUser·p0.999:  20.578 ms/op
                 getUser·p0.9999: 22.924 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   2: 4.156 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   8.258 ms/op
                 getUser·p0.999:  19.628 ms/op
                 getUser·p0.9999: 24.237 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   3: 4.178 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.952 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  13.769 ms/op
                 getUser·p0.9999: 26.979 ms/op
                 getUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229628
  mean =      4.180 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 214714 
    [ 5.000,  7.500) = 10393 
    [ 7.500, 10.000) = 3631 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     26.314 ms/op
     p(99.9990) =     27.299 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.217 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 6.085 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.144 ±(99.9%) 0.020 ms/op
Iteration   1: 4.957 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.357 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  24.740 ms/op
                 listUser·p0.9999: 32.539 ms/op
                 listUser·p1.00:   33.358 ms/op

Iteration   2: 4.987 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   5.587 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  18.900 ms/op
                 listUser·p0.9999: 24.090 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   3: 5.141 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   5.734 ms/op
                 listUser·p0.95:   6.472 ms/op
                 listUser·p0.99:   9.519 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 19.974 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 190959
  mean =      5.027 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 120023 
    [ 5.000,  7.500) = 65636 
    [ 7.500, 10.000) = 3982 
    [10.000, 12.500) = 713 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 171 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.261 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     30.733 ms/op
     p(99.9990) =     33.268 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.486 ± 6.042  ops/ms
ClientPb.existUser                       thrpt       3   7.964 ± 0.732  ops/ms
ClientPb.getUser                         thrpt       3   7.712 ± 2.085  ops/ms
ClientPb.listUser                        thrpt       3   6.472 ± 2.135  ops/ms
ClientPb.createUser                       avgt       3   4.157 ± 2.438   ms/op
ClientPb.existUser                        avgt       3   3.924 ± 0.556   ms/op
ClientPb.getUser                          avgt       3   4.155 ± 0.512   ms/op
ClientPb.listUser                         avgt       3   4.986 ± 0.955   ms/op
ClientPb.createUser                     sample  234677   4.090 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.663           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.578           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.494           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.835           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  244645   3.923 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.509           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.358           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.102           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.949           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.310           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.883           ms/op
ClientPb.getUser                        sample  229628   4.180 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.765           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.628           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.314           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.886           ms/op
ClientPb.listUser                       sample  190959   5.027 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.261           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.201           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.208           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.759           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.733           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.358           ms/op
